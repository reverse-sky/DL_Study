# Object
Implementation for Central Limit Theorem and Learn about the Marcov chain and Monte Carlo by Metropolis-hastings algorithms 

# Summary
+ MCMC_test.ipynb : Jupyter Notebook for testing implementation

Front part have implementation of Central Limit Thorem. 
In mathmatically, Sampling means output of Inverse CDF. but many case, Inverse CDF calculation is very expensive and sometimes it can't caculate. 
So, we have to other method to sample the data. 

First case is Rejection Sampling. This purpose is very simple. First propose a distribution called proposal distribution usually used Uniform distribution. 
Then, Sampling data from proposal distribution and evaluate between proposal output and target output. 
If proposal data value is higher than target value, it will be a acppeted, in other hand other case will rejected. 

That's it! And if iteration num is large, sampling from proposal distribution will concave the target distribution. 
 
Second case is Metropolis-hastings algorithm. It is genally used for MCMC process. 
Algorithm is just simple. New proposal will compare with old method. like $\frac{f(x_{new}|x_{old})}{f(x_{old}|x_{new})} > 1$ 
if new method is better than old method, new method will be selected for sampling. 

plz check jupyter file for specific introduction