[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

```
import nsfg
import thinkstats2
import thinkplot

preg = nsfg.ReadFemResp()
pmf = thinkstats2.Pmf(preg.numkdhh, label='numkdhh')

hist = thinkstats2.Hist(preg.numkdhh, label='numkdhh')
thinkplot.Hist(hist)
thinkplot.Config(xlabel='# Children', ylabel='Count')

Second Chart
pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')
pmf.Mean()

biased = BiasPmf(pmf, label='biased') #Using BiasPmf function created in the book
biased.Mean()
thinkplot.PrePlot(2)
thinkplot.Pmfs([pmf, biased])
thinkplot.Config(xlabel='# Children', ylabel='PMF')
```
