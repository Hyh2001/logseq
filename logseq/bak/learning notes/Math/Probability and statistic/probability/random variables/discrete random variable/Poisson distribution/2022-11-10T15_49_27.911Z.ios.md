Poison distribution is a limiting form of [[binomial distribution]]. Its probability mass function is like
$p(i) =  P\{ X = i \} = e^{-\lambda}\frac{\lambda^i}{i!}$ for $i = 0,1,2,...$ 
## [[expected value]] of [[Poisson distribution]]
$E(x) = \sum xp(x;\lambda) = \lambda$
### proof 
$E(x) = \sum \frac{\lambda^x}{(x-1)!}e^{-\lambda} = \lambda\sum \frac{\lambda^{x-1}}{(x-1)!}e^{-\lambda}$
## [[variance]] of [[Poisson distribution]] 
$V(x) = \lambda$
### proof

We can use excel to help us to calculate the value of a poison distribution. The use of excel function is as follow.
# excel 
```excel 
POISSON.DIST(X,Mean,Cumulative)
```
![[Pasted image 20221007174919.png]]
1. $X$ means the number of  events
2. Mean means the [[expected value]] of events
3. Cumulative is True, then it will calculate the sum of all the events less or equal to $X$. If it is False, then only the probability of $X$ will be given. 

# relationship with other [[distribution]]s 
## 1. [[Poisson distribution]]  and [[Binomial distribution]] 
Poison distribution is an approximation for a [[Binomial distribution]] when $n$ is large and $p$ is small. This can be proved as follow 
### proof 
let $\lambda = np$$P\{X = i\} = \frac{n!}{(n-i)!i!} p^i(1-p)^{n-i} = \frac{n!}{(n-i)!i!}(\frac{\lambda}{n})^i (1-\frac{\lambda}{n})^{n-i} = \frac{n(n-1)\cdot \cdot \cdot (n-i+1)}{n^i}\frac{\lambda^i}{i!}\frac{(1-\lambda/n)^n}{(1-\lambda/n)^i}$For $n$ is very large and $p$ is very small 
$(1-\lambda/n)^n \simeq e^{-\lambda}$  $\frac{n(n-1)\cdot \cdot \cdot (n-i+1)}{n^i} \simeq 1$  $(1-\lambda/n)^i \simeq 1$
Then we get [[Poisson distribution]]. 
We can also calculate the [[expected value]]  and [[variance]] of a poison distribution. They are as follow. 
## 2. [[Poisson distribution]] and [[Exponential distribution]]
see [[exponential distribution and Poisson distribution]] 