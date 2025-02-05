This is a readme file for PUI Homework 3.

Everything needed to run these Notebooks should be included in the script and documented.

*Note that each Notebook contains a few global variables (within the file) so if you are running the script on a Notebook, just make sure all the cells have been run.

ASSIGNMENT 1: DISTRIBUTIONS

I generated 6 sets of 100 samples, with randomly generated sizes (10 < N < 2000) and these were printed for validation/reproducibility sake. I created 6 distributions, 1 from each sample set:
1. Gaussian
2. Poisson
3. Binomial
4. Chi-squared
5. Laplace
6. Wald (or Inverse Gaussian)

Notes:
- Some parameters were set up arbitrarily as noted. The graph titles and documentation should reference those.
- I set the population mean to 50 but that can be arbitrarily set as well.

Observations:

The trend in all distributions plotted was to close in on the central tendency as the sample sizes get larger. The effect on the graph is a large variance on the left end of the x-axis (the smaller sample sizes), that narrows around the population mean (or on the ratio of p*mean in the case of the binomial distribution) as the sample size gets larger.

This supports the Central Limit Theorem (CLT), which states generally that given a sufficiently large sample size, the distribution approximates a normal distribution.

The histogram of all the means (across all distributions) further supports this, demonstrating a normal distribution centered around the population mean.

Shout outs:
Consulted with....Google. Stackoverflow. And classmates Nate Weber, Michelle Ho, Maria Ortiz.


ASSIGNMENT 2: HYPOTHESIS TESTING

There were some changes to the instruction Notebook that were causing me some confustion so I just pasted my own formulas in the new Notebook. The script should run fine.
