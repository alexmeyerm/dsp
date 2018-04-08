[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)
```
import scipy.stats

dist = scipy.stats.norm(loc=178, scale=7.7)
min = dist.cdf(30.48*5 + 2.54*10) # 5'10" in cm
max = dist.cdf(30.48*6 + 2.54)   # 6'1"in cm
min, max, max-min
```
**(0.48963902786483265, 0.8323858654963063, 0.3427468376314737)**
