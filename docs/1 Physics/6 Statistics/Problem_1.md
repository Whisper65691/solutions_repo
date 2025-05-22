# Problem 1

# Simulating Sampling Distributions to Demonstrate the Central Limit Theorem

## Objective

The Central Limit Theorem (CLT) states that the sampling distribution of the sample mean approaches a normal distribution as the sample size increases, regardless of the population’s original distribution. This simulation illustrates the CLT using several distinct population distributions.

## Step-by-Step Plan

### 1. Select Population Distributions

We will use the following types of distributions:

- **Uniform Distribution**: e.g., values uniformly distributed between 0 and 1.
- **Exponential Distribution**: e.g., skewed distribution with rate parameter $\lambda = 1$.
- **Binomial Distribution**: e.g., number of successes in $n = 10$ trials with success probability $p = 0.5$.

### 2. Generate Large Populations

For each distribution, generate a population of 100,000 data points to represent the underlying population.

- Uniform: $U(0, 1)$
- Exponential: $Exp(\lambda = 1)$
- Binomial: $Bin(n = 10, p = 0.5)$

### 3. Perform Sampling

For each population:
- Randomly draw samples of sizes: $n = 5$, $n = 30$, and $n = 100$.
- Repeat the sampling process 1000 times for each sample size.
- Calculate the **sample mean** for each sample.

### 4. Create Sampling Distributions

For each sample size and each population type:
- Plot the distribution of the sample means (sampling distribution).
- Superimpose a normal distribution curve with the same mean and standard deviation.

### 5. Expected Outcome

- As $n$ increases, the sampling distribution of the mean becomes increasingly **normal-shaped**, regardless of whether the original population is uniform, exponential, or binomial.
- This provides a visual demonstration of the Central Limit Theorem.

---


