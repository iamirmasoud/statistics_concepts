# Implementation of Statistics Concepts in Python

## About this Repo
This repository contains notebooks covering various statistics concepts in Python. Each concept has its own directory containing relevant notebooks and data.

## Preparing the environment
**Note**: I have tested the codes on __Linux__. It can surely be run on Windows and Mac with some little changes.

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/iamirmasoud/statistics_concepts.git
cd statistics_concepts
```

2. Create (and activate) a new environment, named `stats_env` with Python 3.7. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	```shell
	conda create -n stats_env python=3.10
	source activate stats_env
	```
	
	At this point your command line should look something like: `(stats_env) <User>:statistics_concepts <user>$`. The `(stats_env)` indicates that your environment has been activated, and you can proceed with further package installations.

3. Before you can experiment with the code, you'll have to make sure that you have all the libraries and dependencies required to support this project. You will mainly need Python3.7+ and PySpark. You can install  dependencies using:
```
pip install -r requirements.txt
```

4. Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```shell
cd statistics_concepts
```

5. Open the directory of notebooks, using the below command. You'll see all files appear in your local environment; open the first notebook and follow the instructions.
```shell
jupyter notebook
```

6. Once you open any of the project notebooks, make sure you are in the correct `stats_env` environment by clicking `Kernel > Change Kernel > stats_env`.




## Table of Contents

#### [AB Testing](ab_testing)
A/B testing is a statistical technique used to compare two groups of data to determine if there is a significant difference between them. This folder contains notebooks covering the theory behind A/B testing, as well as practical examples of how to conduct and interpret the results of A/B tests.

#### [Advanced Topics](advanced_topics)
This folder contains notebooks covering more advanced topics in statistics, such as Bayesian linear regression, Gibbs sampling, and Thompson sampling.

#### [Confidence Interval](confidence_interval)
A confidence interval is a range of values that is likely to contain a population parameter with a certain degree of confidence. This folder contains notebooks covering how to build confidence intervals and interpret the results.

#### [Hypothesis Testing](hypothesis_testing)
Hypothesis testing is a method of making decisions using data from a sample. This folder contains notebooks covering the theory behind hypothesis testing, as well as practical examples of how to conduct and interpret the results of hypothesis tests.

#### [Linear Regression](linear_regression)
Linear regression is a method used to model the relationship between two variables by fitting a linear equation to the observed data. This folder contains notebooks covering the theory behind linear regression, as well as practical examples of how to fit and interpret linear regression models.

#### [Logistic Regression](logistic_regression)
Logistic regression is a statistical technique used to model the probability of a certain event occurring. This folder contains notebooks covering the theory behind logistic regression, as well as practical examples of how to fit and interpret logistic regression models.

#### [Multiple Linear Regression](multiple_linear_regression)
Multiple linear regression is a method used to model the relationship between several independent variables and a dependent variable by fitting a linear equation to the observed data. This folder contains notebooks covering the theory behind multiple linear regression, as well as practical examples of how to fit and interpret multiple linear regression models.

#### [Practical Statistics](practical_statistics)

This folder contains notebooks covering basic concepts of inference, confidence intervals, hypothesis testing, and linear regression interpretation.

#### [Sampling Distributions and Central Limit Theorem](sampling_distributions_and_central_limit_theorem)
This folder contains notebooks covering sampling distributions, the law of large numbers, the central limit theorem, and bootstrapping.



## Structure of repo
```
├── ab_testing
│   ├── 0-Theory.ipynb
│   ├── 1-Homepage Experiment Data.ipynb
│   ├── 2-enrollment_rate.ipynb
│   ├── 3-average_reading_duration.ipynb
│   ├── 4-average_classroom_time.ipynb
│   ├── 5-completion_rate.ipynb
│   ├── data
│   └── imgs
├── advanced_topics
│   ├── Bayesian Regression with PyMC3.ipynb
│   ├── Bayesian Treasure Hunt.ipynb
│   ├── data
│   ├── Gibbs Sampling Code.ipynb
│   ├── MCMC Board Game.ipynb
│   ├── MCMC Experiments.ipynb
│   ├── Monte Carlo Code.ipynb
│   ├── Probability Calibration.ipynb
│   ├── Sample Size.ipynb
│   └── Thompson Sampling.ipynb
├── confidence_interval
│   ├── 1-Building Confidence Intervals.ipynb
│   ├── 2-Difference in Means.ipynb
│   ├── 3-Traditional Confidence Intervals.ipynb
│   ├── data
│   └── README.md
├── hypothesis_testing
│   ├── 0-Theory.ipynb
│   ├── 1-Test-Using CI to make decisions.ipynb
│   ├── 2-Test-Simulating Null to make decisions.ipynb
│   ├── 3-Simulating from the Null.ipynb
│   ├── 4-Drawing Conclusions - Calculating Errors .ipynb
│   ├── 5-Other Things to Consider - Multiple Testing.ipynb
│   ├── 6-What is the impact of sample size.ipynb
│   ├── data
│   └── imgs
├── linear_regression
│   ├── 0-Theory.ipynb
│   ├── 1-The Regression Closed Form Solution.ipynb
│   ├── 2- HousingAnalysis.ipynb
│   ├── 3- RegressionCaratsVPrice.ipynb
│   ├── 4-HomesVCrime.ipynb
│   ├── data
│   └── imgs
├── logistic_regression
│   ├── 0-Theory.ipynb
│   ├── 1-Fitting Logistic Regression.ipynb
│   ├── 2-Interpret Results.ipynb
│   ├── 3-Model Diagnostics.ipynb
│   ├── 3-Model Diagnostics - Solution.ipynb
│   ├── data
│   └── imgs
├── multiple_linear_regression
│   ├── 0-Theory.ipynb
│   ├── 1-Multiple Linear Regression Introduction.ipynb
│   ├── 2-Interpreting Model Coefficients.ipynb
│   ├── 3-DummyVariables.ipynb
│   ├── 4-One_Zero_Negative_One Coding.ipynb
│   ├── 5-Multicollinearity & VIFs.ipynb
│   ├── 6-Case Study.ipynb
│   ├── 7-Feature Engineering.ipynb
│   ├── books
│   ├── data
│   └── imgs
├── practical_statistics
│   ├── 0_ Inference - Basic Concepts
│   ├── 1_ Inference - Confidence Interval
│   ├── 2_ Inference - Hypothesis Testing
│   └── 4_ Linear Regression - Interpreting Results and Model Performance
├── README.md
├── requirements.txt
└── sampling_distributions_and_central_limit_theorem
    ├── 0-Theory.ipynb
    ├── 1-Create Sampling Distribution.ipynb
    ├── 2-Law of Large Numbers.ipynb
    ├── 3-Central Limit Theorem.ipynb
    ├── 4-Central Limit Theorem - Part II.ipynb
    ├── 5-Central Limit Theorem - Part III.ipynb
    ├── 6-Bootstrapping.ipynb
    └── imgs

```