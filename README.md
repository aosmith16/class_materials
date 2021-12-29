## Class materials

These are readings and analysis code I created when filling in teaching a graduate-level class that went over linear models, linear mixed models, and basic generalized linear models for non-statisticians. It might described as almost an "experimental design" class. Examples discussed tend to be from natural resources. 

I inherited the class as lecture style and ultimately flipped it, updated the material, and converted all lecture material to short (ish) readings. Lecture meeting times were dedicated to questions, a low stakes quiz on the material, and activities. 

### Outline of topics for each class

This is my rough overview of the 8 weeks of class topics, starting with class 1.2 since 1.1 was dedicated to introducing the class.

**Class 1.2: Scope of inference**    
1. Statistics, sampling and study design    
    a. The discipline of statistics    
    b. What is a statistic?    
    c. Why we use statistics    
    d. Sampling    
    e. Distributions    
    f. Study design    
2. Scope of inference    
    a. Example of extending the scope of inference    
    b. Representation    
    c. Randomization    
    d. Replication    

**Class 2.1: Sources of variation**     
1. Appropriate Language    
    a. Research question    
    b. Results    
2. Sources of variation    
    a. Fixed vs random    
    b. Minimize unexplained variation    
3. Statistical model    
    a. Types of research goals    
    b. Basis of statistical model    
    c. Statistical model defines analysis    
4. Language about response variables    
    
**Class 2.2: Assumptions**    
1. Checking model assumptions    
    a. How to check model fit    
    b. Assumptions    
    c. Additivity of effects    
    d. Independence of errors    
    e. Constant variance of errors    
    f. Normality of errors    
2. Reporting results    
    a. Hypothesis tests    
    b. Estimates and confidence intervals    
3. Making conclusions    
    a. Limitations    
    
**Class 3.1: Random effects and blocking**    
1. Random effects    
    a. Fixed vs random    
    b. Observation-level random effect    
2. Blocking	    
    a. Blocking factors    
    b. Study example – no blocking needed    
    c. Study example – factor confounded with blocking variable    
    d. Study example – randomized complete block design    
    e. Assumptions about blocking    
    f. Blocking and independence    
3. Statistical model and analysis    
    a. Blocking variable random effect    
    b. Independence of errors    
    c. Two variances    

**Class 3.2: Multiple comparisons and power**    
1. Multiple comparisons    
    a. Type I and Type II errors    
    b. Beyond Type I and Type II errors    
    c. When to use an adjustment    
    d. Options for adjustments in emmeans    
2. Inconclusive results    
    a. Issue of sample size    
    b. Issue of variation    
    c. Limitations    
3. Power analysis    
    a. Basic approach    
    b. Why do a power analysis?    
4. Simulations    

**Class 4.1: Factorial**    
1. Multiple factors of interest    
    a. Crossed factors    
    b. Simple effects    
2. Factorial design    
    a. Interaction effects    
    b. Overall (main) effects    
    c. Language when working with multiple factors    
    d. Interaction or not?    
    e. Main effects in the presence of an interaction    
3. Statistical model and analysis    

**Class 4.2: Transformations**    
1. Transformations    
    a. Change relative spacing    
    b. Change relationships    
    c. Why transform?    
    d. Types of transformations    
    e. Alternatives to transformation    
2. The log-normal distribution    
    a. What about zeros?    
    b. Multiplicative models    
    c. Inference to medians    
    d. Multiplicative differences    
3. Percentages    
    a. Percentage change vs ratios    

**Class 5.1: Multiple random effects**    
1. Studies with different sizes of physical units    
2. Nested vs crossed factors    
    a. Crossed factors    
    b. Nested factors    
    c. Partial crossing    
    d. Crossed random effects    
3. Explicit naming    
    a. Missing column for physical units    
    b. Making explicit names    
4. Statistical model and analysis    
    a. Random effects    
    b. Overall tests    
    
**Class 5.2: Continuous explanatory variables**
1. Continuous explanatory variables    
    a. Intercepts and slopes    
    b. Linear relationship    
    c. Linearity and scale    
    d. Confidence interval around relationship    
    e. Spurious correlations    
    f. Physical units of different sizes    
2. Working with continuous and categorical variables    
    a. Parallel lines    
    b. Separate lines    
    c. Continuous by continuous interactions    
3. Analysis with many variables    
    a. Hard thinking    
    b. How many variables can I use?    
    c. Model complexity    
    d. Approach to explore the data    
    e. Interpretation and added variable plots    
4. Model selection    
    a. Known problems with model selection    
    b. Explain vs predict    
    c. Competing models	    

**Class 6.1: Repeated measures**    
1. Introduction to repeated measures    
    a. Repeated measures in time    
    b. Repeated measures in space    
    c. Design details    
    d. Analysis options    
2. Assumptions about repeated measures models    
    a. Independence of subjects    
    b. Within subject dependence    
    c. Constant variance    
3. Correlation    
    a. Positive correlation    
    b. Negative correlation    
    c. Checking for correlation    
    
**Class 6.2: Correlation structures**    
1. Correlation matrix    
    a. Matrix showing no correlation    
    b. Matrix showing correlation    
    c. Correlation matrix with symbols    
    d. Covariance matrix    
2. Specific correlation structures    
    a. Mixed model induced correlation    
    b. Compound symmetry    
    c. AR1    
    d. General correlation    
    e. Correlations available in nlme    
3. Choosing a correlation structure    
    a. For longer series    
    b. For short series    
    c. Information criteria    
    d. Algorithm for choosing a correlation structure for a short series    
    e. Written description of algorithm    
4. Model description and analysis    
    a. Describe correlation in words    
    b. R details    
5. Equivalence testing    

**Class 7.1: Generalized linear models**    
1. Introduction to generalized linear models    
    a. Model equation    
    b. Probability model    
    c. Canonical link function    
    d. Generalized linear model overview    
    e. “General” linear model    
2. Types of response variables    
    a. Continuous and symmetric    
    b. Positive continuous and right-skewed    
    c. Counts    
    d. Counted proportions    
    e. Presence/absence    
    f. Continuous proportions    
    g. Positive continuous with a point mass at 0    
    h. Variance depends on mean    
    i. Error distribution    
    j. Transformation    
3. Binomial generalized linear model    
    a. Probability model    
    b. Logit link    
    c. Model scale    
    d. Odds scale    
    e. Data scale    

**Class 7.2: Binomial GLM**    
1. Overdispersion    
    a. Causes of overdispersion    
    b. Alternatives    
    c. Binary data and overdispersion    
    d. Underdispersion    
2. Complete separation    
    a. Causes of and solutions to    
    b. Alternatives when you have complete separation    
    c. Quasi-complete separation    
3. Fitting a binomial GLM    
    a. Response variable    
    b. Check for overdispersion    
    c. Complete separation    
    d. Role of residuals    
    e. Hypothesis tests and confidence intervals    
    f. Results    
4. Output from R    

**Class 8.1: GLM for counts**    
1. Generalized linear models for counts    
    a. Negative binomial distribution    
    b. Poisson distribution    
    c. Probability model    
    d. Link function    
    e. Zeros and complete separation    
    f. Count per unit effort    
2. Fitting a negative binomial GLM    
    a. Check variance/mean relationship (like overdispersion)    
    b. Residual plots    
    c. Tests and confidence intervals    
    d. Results    
    e. Practically important change in a continuous explanatory variable    
    f. Plotting results with multiple continuous explanatory variables    
3. Output from R    

**Class 8.2: Zero inflation and GLMM's**    
1. Fitting a Poisson GLM    
    a. Checking for overdispersion    
    b. Residual plots    
    c. Tests and confidence intervals    
    d. Results    
    e. Alternatives to the Poisson distribution    
2. Zero inflation    
    a. Having lots of zeros isn’t necessarily zero inflation    
    b. Modeling options for zero inflated data    
    c. Hurdle model    
    d. Zero inflated model    
3. Generalized linear mixed models    
    a. Difficulties with GLMM’s    
    b. Residual plots    
    c. Repeated measures and GLMM’s    

## Lab materials

Lab periods were dedicated to learning how to analyze the a dataset in R based on the topic/analysis introduced that week.

### Topics

1. Intro to R (t-test)
2. Separate means model (ANOVA)
3. Linear mixed model
4. Factorial linear mixed model
5. Factorial linear mixed model with nested random effects
6. Extending the linear mixed model with correlation structures
7. Binomial generalized linear model
8. Negative binomial generalized linear model (continuous explanatory variable)
