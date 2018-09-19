[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)



```python
import scipy.stats
```

```python
dist = scipy.stats.norm(loc=178, scale=7.7)
```

```python
dist.cdf(185.4)- dist.cdf(177.8) 
```



```
0.3420946829459531
```



34 % of US male population is between 5'10'' and 6'1''