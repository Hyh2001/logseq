---
alases:[Gaussian distribution]
---
Normal distribution is also called Gaussian distribution. We say that $X$ is normally distributed with parameters $\mu$ and $\sigma^2$, if the density of $X$ is given that
$f(x) = \frac{1}{\sqrt{2\pi}\sigma}e^{-(x-\mu)^2/2\sigma^2}$    $-\infty<x<\infty$
The property of the distribution is as follow:
1. The density function is symmetric about $\mu$, so $\mu$ determines the shape of the curve.  
2. $\sigma$ will control the shape of the curve. 
# normal distribution of functions of [[random variable]] 
Let $Y = aX + b$, if $X$ is normally distributed with parameters $\mu$ and $\sigma$, then $Y$ is normally distributed with $a\mu +b$ and $a^2\mu^2$.  To proof this we can see below:
## proof
We denote that the cumulative distribution function of $Y$ is 
$F_Y(x) = P\{ Y \leq x\} = P\{aX + b \leq x\} = P\{X \leq \frac{x-b}{a}\} = F_x(\frac{x-b}{a})$
Next we differentiate the function and we get
$f_Y(x) = \frac{1}{a} f_x(\frac{x-b}{a}) = \frac{1}{\sqrt{2\pi}a\sigma}e^{-(x-b-a\mu)^2/2(a\sigma)^2}$

Also, with this property, we can define [[standard normal distribution]]. 
# approximate binomial distribution 
Normal distribution can be also used to approximate [[Binomial distribution]]. It can be seen in [[normal distribution and binomial distribution]]  

