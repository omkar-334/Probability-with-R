# Probability Distributions  
  
![699rule](https://github.com/omkar-334/Probability-with-R/assets/40126336/23365dd3-ce1c-4138-8c1b-67cef1bd48c8)  
![normal](https://github.com/omkar-334/Probability-with-R/assets/40126336/9b3d0fdc-90c1-4a23-89df-9d0be10b76c8)  
![zscore](https://github.com/omkar-334/Probability-with-R/assets/40126336/a190b43c-87f4-491e-a0e1-b357cccaa75d)  
![percentile](https://github.com/omkar-334/Probability-with-R/assets/40126336/d59ca6e6-7e4b-464e-a35e-f80fc268177f)  

#### R functions  
	dnorm: density function of the normal distribution (pdf)  
	pnorm: cumulative density function of the normal distribution (cdf)  
	qnorm: quantile function of the normal distribution (inverse cdf)  
	rnorm: random sampling from the normal distribution  
	choose(9,2) - Combination  
  
#### Probability functions  
	The probability of getting a no. of successes(k) in a no. of trials(size) where the probability of success on each trial is fixed.(p)  
	dbinom(k,size=n,p=p) -   
	sum(dbinom(k1:k2,size=n,p=p)) - Adds all the probabilities from k1 to k2  
  
#### Normal Probability plot  
	Y-axis - Data  
	X-axis - Theoretical quantiles  
	One-to-one relationship - nearly normal distribution  
	(Perfect straight line on a scatter plot)  
  
	Right skew - points bend up and to the left of the line  
	Left skew - points bend down and to the left of the line  
	If points are spread out, they are more variable  
	Left skewed distribution - Mean<Median - Positive Z Score  
![skew](https://github.com/omkar-334/Probability-with-R/assets/40126336/d7612c5f-1c34-46fd-8882-477dd35c935c)  

#### Bernoulli random variable  
	When an individual trial can have only 2 possible outcomes - a success and a failure  
  
#### Binomial distribution conditions  
	1.The trials must be independent  
	2.The number of trials, n , must be fixed.  
	3.Each trial outcome must be classified as a success or a failure  
	4.The probability of success, p, must be same for each trial.  
![binomial](https://github.com/omkar-334/Probability-with-R/assets/40126336/4a8962ec-901f-465a-a522-2e0f5a546b80)  
![npf](https://github.com/omkar-334/Probability-with-R/assets/40126336/f0f92750-a695-46eb-9445-c6e528d62fc4)  
  
#### Normal Approximations  
		As sample size increases, binomial distributions start to look like normal distributions  
		n=size, p=p(success), f=1-p  
		Mean=np  
		SD=root npf  
![s/f](https://github.com/omkar-334/Probability-with-R/assets/40126336/7122a09c-25aa-4457-8643-6fde91fa12ba)  

**Suggested Readings for this week:** [OpenIntro Statistics, 3rd edition](https://www.openintro.org/stat/textbook.php?stat_book=os), Chapter 3, Sections 3.1 - 3.2, 3.4  
**Practice exercises:** End of chapter exercises Chapter 3: 3.3, 3.5, 3.7, 3.9, 3.11, 3.17, 3.25, 3.27, 3.29, 3.33.  
