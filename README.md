The workings for a very interesting exercise from the Econometrics of Financial Markets 
module of the MSc Quantitative Finance course at Bayes Business School (formerly Cass).

Excerpt from the paper:

An 𝑛 period realised volatility can be computed by the summation of all 𝑚 period 
squared returns within the 𝑛 period.

$$
\sigma^2_n = \sum_{i=1}^{m} r_i^2
$$

The use of alternative volatility measures is an important consideration when working with 
high-frequency data. Existing literature suggests there are significant benefits to using 
alternative dispersion measures in forecasting via stochastic volatility models. It is found 
by Blair, Poon, and Taylor (2001) that the VIX index is a coherent measure of volatility as 
evidenced through robust ARCH results and high degree of correlation between the VIX implied 
volatility and the realised volatility measured during the same periods. Andersen and Benzoni (2008) 
extend the discussion to a more generalised framework by developing concepts around the relation 
between conditional return variance against and their quadratic variation and realised volatility. 

The study conducted by Blair, Poon, and Taylor (2001) demonstrates that using the VIX index to 
forecast volatility yields more accurate results compared to any conditional variance estimation method 
and choice of time series frequency. The VIX index naturally contains a greater amount of information 
pertaining to leverage effects and market perception by virtue of the VIX being a measure of implied 
volatility in the aggregated options market. It is also found that measures of realised volatility generally 
outperform the traditional counterparts, especially as a leading indicator of future volatility. The intuition 
behind realised volatility computed from high-frequency returns is that the data is closer to a 
continuous time representation. Intraday frequencies for long time series are considerably more granular 
than traditional approaches and will capture shorter-term dynamics of the data. Naturally, there are 
limitations in the fact that such high frequency will potentially also capture unwanted elements such as, 
microstructure noise, herding effects, or other idiosyncratic disruptions to the information content of the data.
