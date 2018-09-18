[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)



```python
import nsfg
import math
```

```python
df=nsfg.ReadFemPreg()
```

```python
weight_first=df.totalwgt_lb[df['pregordr'] == 1]
```

```python
weight_other=df.totalwgt_lb[df['pregordr'] >1]
```

```python
def CohenEffectSize(group1, group2):
    diff = group1.mean() - group2.mean()

    var1 = group1.var()
    var2 = group2.var()
    n1, n2 = len(group1), len(group2)

    pooled_var = (n1 * var1 + n2 * var2) / (n1 + n2)
    d = diff / math.sqrt(pooled_var)
    return d
```

```python
CohenEffectSize(weight_first,weight_other)
```



```
-0.06911825348820934
```



The difference in means is -0.069 standard deviations. It is larger that the difference in pregnancy lengh but is still small.