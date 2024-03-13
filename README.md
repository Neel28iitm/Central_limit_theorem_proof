# Central_limit_theorem_proof
CLT states that the distribution of the sample means of a large numbers of independent and identically distributed random variables will approach a normal distribution regardless of the underlying distribution of the variables.
Here I follow  some steps:
step1: Generating population salaries of 1,00,000 people assuming it follows lognormal distribution(we can take any distribution) , we can also take any dataset also.
Step2: Taking random sample size of 50(sholud be>30) people data among population that i have generated.
step3: Taking 1000 such samples and calculating the mean(sample mean) of all 50-50 sets i.e.., we have 1000 sample mean and similary 1000 standard deviations.
step5:avg mean of sample=avg mean of population and avg std dev of sample =avg std dev of population/sqrt(sample size).
Step4: Calculating the average of the sample mean. This will be our first best estimate of the population mean.
step5: calculating the range by taking 95% confidence interval, and we see that our predicted population salary of sample lies in that range.
Also plot is justifying the statement of CLT.
