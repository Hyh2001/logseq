Choose a sample size of $n$ randomly from $N$ balls without replacement, of which $m$ are white and $N-m$ are black. We let $X$ denote the number of white balls. Then
$P\{x = i\} = \frac{C^{m}_i C^{N-m}_{n-i}}{C^{N}_{n}}$
# [[expected value]] of [[Hypergeometric distribution]] 
The expected value of 
# excel
```excel
HYPERGEOM.DIST(sample_s,number_sample,population_s,number_pop,cumulative)
```