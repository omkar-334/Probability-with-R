#### Random process  
We know what possible outcomes could happen but not what particular outcomes will happen  
0<=P(A)<=1  

![probability](https://github.com/omkar-334/Probability-with-R/assets/40126336/07a504d6-27a7-4b95-b546-5db9fbba1728)  
  
#### Law of large numbers  
		As more observations are collected, the proportion of occurences with a particular outcome converges to the probability of that outcome.  
		P(heads) in   
		10 throws /=/ 0.5  
		1000 throws = 0.5  
  
Objects are memoryless  
The next outcome does not depend on the previous outcome  
  
#### Gambler's fallacy(Law of averages)  
		Random processes are expected to compensate for previous outcomes  
  
#### Disjoint events  
				Mutually exclusive events cannot happen at the same time  
				A student canot both fail and pass a class.  
				P(A and B)=0  
![disjoint](https://github.com/omkar-334/Probability-with-R/assets/40126336/1ba36cbf-693f-4c4d-8043-cd18c64cc35a)  
![djunion](https://github.com/omkar-334/Probability-with-R/assets/40126336/0785243d-4b48-41c0-a52b-884932e58bce)  
![nondjunion](https://github.com/omkar-334/Probability-with-R/assets/40126336/1141dc1c-12f9-4bf3-8d36-50798fca875b)  
  
#### General Addition Rule  
		P(A or B) = P(A) + P(B) - P(A and B)  
  
#### Sample Space  
A collection of all possible outcomes of a trial  
  
#### Probability Distribution  
		Lists all possible outcomes in the sample space and the probabilities with which they occur.  
		Rules  
		  1.Events listed must be disjoint.  
		  2.Each probability must be between 0 and 1.  
		  3.The sum of probabilities must be 1  
  
#### Complementary Events  
		Two Mutually exclusive events whose probabilities add up to 1.  
		Complementary Events are always disjoint  
		Disjoint Events are not always complementary  
  
#### Independence  
		Two processes are independent if knowing the outcome of one provides no useful information about the outcome of the other.  
		Ex - two coin tosses  
		If P(A|B)=P(A), then A and B are independent  
		(Probability of A, given B)
![dependence](https://github.com/omkar-334/Probability-with-R/assets/40126336/16681f8d-72ee-47de-a0d8-2e8bf20e3dd2)  
![independence](https://github.com/omkar-334/Probability-with-R/assets/40126336/ac3c4118-0039-4f0e-8dd7-9e763da3060c)  
  
#### Product Rule  
If A and B are independent, P(A and B) = P(A) x P(B)  
  
Larger the sample size, the more convincing the evidence from that sample.  
  
#### Conditional Probability  
		P(A|B)  
		The likelihood of an event or outcome occurring, based on the occurrence of a previous event or outcome  

#### Marginal Probability  
		P(B)  
		The probability of an event occurring (P(B)), it may be thought of as an unconditional probability.  

#### Joint Probability  
		P(A and B)
		A statistical measure used to calculate the likelihood of two events taking place at the same time.  
		Both events must be independent of each other.  
		Joint probability is also called the intersection of two or more events.  

#### Posterior Probability  
		P(hypothesis|data) - Probability of a hypothesis we set forth , given the data we just collected.  
		It depends on both the prior probability and the observed data  
		It is also called a p-value  

#### Bayes’ theorem  
		P(A∣B)= P(A and B)/P(B)  
		Bayesian Inference  

#### Probability Trees  
![probtree](https://github.com/omkar-334/Probability-with-R/assets/40126336/2ff97495-fa1e-40e2-bfa0-fe2ba0b1c899)  
![problem](https://github.com/omkar-334/Probability-with-R/assets/40126336/99c34520-fb44-4cbb-869e-2e45e6bcd326)  

**Suggested reading**: Chapter 2, Sections 2.1 and 2.2  
**Practice exercises**: Chapter 2: 2.1, 2.3, 2.5, 2.7, 2.13, 2.15, 2.19, 2.21, 2.23  


