# Advanced-Statistics-Assignment
Task 1: Basic Probabilities and Visualizations 
Please provide the requested visualization as well as the numerical results. In both cases, please either prove or
cite any computation of the proof steps (calculations, code, steps, etc.), and justify why you trust the tools you
used. Do not forget to include the scale of each graphics so that the reader can interpret the numbers represented.
As indicated in the remark above, only perform one of the following tasks based on your personal value of 𝜉1:
If 𝜉1 is 0: A vote with the outcome 𝑓𝑜𝑟 or 𝑎𝑔𝑎𝑖𝑛𝑠𝑡 follows a Bernoulli distribution where 𝑃(vote =
"𝑓𝑜𝑟") = 𝜉2.
Represent the proportion of “for” and “against” in this single Bernoulli trial using a graphic and a percentage. Can
an expectation be calculated? Justify your answer with all necessary hypotheses.
If 𝜉1 is between 1 and 3:
The number of meteorites falling into an ocean in a given year can be modeled by one of the following
distributions. Provide a graphic showing the probability of one, two, three, etc., meteorites falling (until the
probability remains less than 0.5% for any higher number of meteorites; you should also prove it). Calculate the
expectation and median and present them in this graphic:
• If 𝜉1 is 1: a Poisson distribution with an expectation of 𝜆 = 𝜉2
• If 𝜉1 is 2: a negative binomial distribution with an expectation of 𝑘 = 𝜉2 and 𝑝 = 𝜉3
• If 𝜉1 is 3: a geometric distribution counting the number of Bernoulli trials with 𝑝 = 𝜉2 until it succeeds.

Task 2: Basic Probabilities and Visualizations 
Let 𝑌 be the random variable with the time it takes to hear an owl from your room’s open window (in hours).
Assume that the probability that you still need to wait to hear the owl after 𝑦 hours is one of the following
functions:
• If 𝜉4 is 0: the probability is given by 𝜉5e−𝜉6 𝑦 + 𝜉7e−𝜉8 𝑦
• If 𝜉4 is 1: the probability is given by 𝜉5e−𝜉6 𝑦2+ 𝜉7e−𝜉8 𝑦8
• If 𝜉4 is 2: the probability is given by 𝜉5e−𝜉6 √𝑦 + 𝜉7e−𝜉8 √𝑦3
• If 𝜉4 is 3: the probability is given by 𝜉5e−𝜉6 𝑦2+ 𝜉7e−𝜉8 𝑦2
Find the probability that you need to wait between two and four hours to hear the owl, and compute and display
the probability density function graph, as well as a histogram where each bar represents the probability of the
hearing the owl at any particular minute. Compute and display in the graphics the mean, variance, and quartiles
of the waiting times.
Please pay attention to the various units of time and make sure that the parameters you receive are such that
𝜉5 + 𝜉7 = 1.

Task 3: Transformed Random Variables
A type of network router has a bandwidth total to first hardware failure called 𝑆 expressed in terabytes. The
random variable 𝑆 is modeled by an exponential distribution whose density is given by one of the following
functions:
• If 𝜉9 = 0: 𝑓 𝑆(𝑠) =1θ𝑒−𝑠θ
• If 𝜉9 = 1: 𝑓 𝑆(𝑠) =124θ5 𝑠4𝑒−𝑠θ
• If 𝜉9 = 2: 𝑓 𝑆(𝑠) =1120𝜃7 𝑠6𝑒−𝑠θ
with a single parameter 𝜃. Consider the bandwidth total to failure 𝑇 of the sequence of the two routers of the
same type (one being brought up automatically when the first is broken).
Express 𝑇 in terms of the bandwidth total to failure of single routers 𝑆1 and 𝑆2. Formulate realistic assumptions
about these random variables. Calculate the density function of the variable 𝑇.
Given an experiment with the dual-router-system yielding a sample 𝑇1 , 𝑇2 , …, 𝑇𝑛 , calculate the likelihood
function for 𝜃. Propose a transformation of this likelihood function whose maximum is the same and can be
computed easily.
An actual experiment is performed, and the infrastructure team has obtained the bandwidth totals to failure given
by the sequence 𝜉10 of numbers. Estimate the model-parameter with the maximum likelihood and compute the
expectation of the bandwidth total to failure of the dual-router-system.

Task 4: Hypothesis Test
Over a long period of time, the production of 1,000 high-quality hammers in a factory seems to have reached a
weight with an average of 𝜉11 (in 𝑔) and standard deviation of 𝜉12 (in 𝑔). Propose a model for the weight of the
hammers including a probability distribution for the weight. Provide all the assumptions needed for this model
to hold (even the uncertain ones). What parameters does this model have?
One aims to answer one of the following questions about a new production system:
• (if 𝜉13 = 0): Does the new system make more constant weights?
• (if 𝜉13 = 1): Does the new system make lower weights?
• (if 𝜉13 = 2): Does the new system make higher weights?
• (if 𝜉13 = 3): Does the new system make less constant weights?
To answer this question, a random sample of newly produced hammers is evaluated yielding the weights in 𝜉14.
What hypotheses can you propose to test the question? What test and decision rule can you make to estimate
whether the new system answers the given question? Express the decision rules as logical statements involving
critical values. What error probabilities can you suggest and calculate? Perform the test and draw the conclusion to answer the question.

Task 5: Regularized Regression
Given the values of an unknown function 𝑓: ℝ → ℝ at some selected points, we try to calculate the parameters
of a model function using OLS as a distance and a ridge regularization:
• (if 𝜉15 = 0): a polynomial model function of twelve 𝛼𝑖 parameters: 𝑓(𝑥) = 𝛼0 + 𝛼1𝑥 + 𝛼2𝑥2 + ⋯ +
𝛼12𝑥12
• (if 𝜉15 = 2): a polynomial model function of ten 𝛼𝑖 parameters: 𝑓(𝑥) = 𝛼0 + 𝛼1𝑥 + 𝛼2𝑥2 + ⋯ +
𝛼10𝑥10
Calculate the OLS estimate, and the OLS ridge-regularized estimates for the parameters given the sample points
of the graph of 𝑓 given that the values are (𝑥, 𝑦) each of the elements of 𝜉16. What weight do you give to the
penalties? What are the qualities of each of the solutions?
Remember to include the steps of your computation, which are more important than the actual computations. If
you calculate the solution with a program, make sure that you trust and cite the core functions used and that you
sketch the mathematical path in a way that is coherent with the program.
Task 6: Bayesian Estimates
Following Hogg et al. (2020), exercise 11.2.2:
Let 𝑥1, 𝑥2 …, 𝑥10 be a random sample from a gamma distribution with 𝛼 = 3 and 𝛽 = 1/𝜃. Suppose we believe
that 𝜃 follows a gamma-distribution with 𝛼 = 𝜉17 and 𝛽 = 𝜉18 and suppose we have a trial (𝑥1, … , 𝑥𝑛) with an
observed 𝑥̅= 𝜉19.
a) Find the posterior distribution of 𝜃.
b) What is the Bayes point estimate of 𝜃 associated with the square-error loss function?
c) What is the Bayes point estimate of 𝜃 using the mode of the posterior distribution?

  
