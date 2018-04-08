[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

```
ran = np.random.random(1000)

pmf = thinkstats2.Pmf(ran)
thinkplot.Pmf(pmf, linewidth=0.05)
thinkplot.Config(xlabel='number', ylabel='PMF')

cdf = thinkstats2.Cdf(ran)
thinkplot.Cdf(cdf, linewidth=1)
thinkplot.Config(xlabel='number', ylabel='CDF')
```
