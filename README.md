# data-science-studies

Data Science studies

# Python pandas:

- import of data in csv, xlsx, html, json and txt examples
- filters type, reorders indexes
- data series/data frames from tuples, dictionaries and lists
- concat data frames
- filter and sort dataframe, export data
- dataframe selection
- treatment of missing data
- series interpolation
- aggregate new calculated columns to a data frame
- removing columns from a data frame
- frequency distribution
- descriptive statistics extracting the count / mean / std / min / 25% / 50% / 75% / max from a dataframe
- plot using matplotlib.pyplot (boxplot, histogram, scatterplot)
- creates value ranges by cutting dataframes
- identify and removes outliers

# Statistics

## Frequencies and measurements

        - FREQUENCY DISTRIBUTION
            - Frequency distribution for qualitative variables
            - Frequency distribution for quantitative variables (custom classes)
            - Creation of frequency distributions with pandas `value_counts()`, `crosstab()` and  with custom classes, using the `value_counts()` and `cut()` functions together.
            - Use of Sturges rule to obtain an optimal number of classes for a given sample size.
            - Plot the histograms with pandas and seaborn
        - Mean, median and mode
            - Calculates the main measures of central tendency: arithmetic mean, median and mode.
            - Indentifies important characteristics of a distribution, such as the presence of asymmetry and its direction from the relationship between measures of central tendency.
        - Measures of position
            - Obtainment of quartiles, deciles and percentiles of a distribution
            - Building and interpreting a boxplot, using quartiles
        - Dispersion measures
            - Obtainment three important dispersion measures. The mean absolute deviation, the variance and the standard deviation.
        - Descriptive analysis of The National Household Sample Survey - PNAD of 2015, that  investigates general characteristics of the population, education, work, income and others, which we could reveal some interesting information, including the following highlights:
        - Income Density Inequality by States in Brazil
        - In general women are more educated than men
        - Women have lower income than men regardless of color
        - White and yellow people income are considerably higher than black people
        - Men have a substantially higher income than women, even though they have the same amount of years of study
        - 99% of the Brazilian population in 2015 had a maximum income of R$ 15000
        - In terms of income, in 2015, the vast majority of the Brazilian population fell into category E (maximum 2 minimum wages)

## Probability and sampling:

    - Binomial distribution:
        - The basic concepts of the binomial probability distribution
        - How to identify and solve problems that involve a binomial experiment
        - How to obtain the probability of events that involve only two possibilities of result
    - Poisson distribution
        - The basic concepts of the Poisson probability distribution
    - Normal distribution
        - The basic concepts of normal probability distribution
        - Working with the standardized table Z
        - How to obtain the probabilities using the normal distribution in a set of situations
    - Sampling techniques
        - Concepts of population and sample
        - The identification of finite and infinite populations
        - When to use the sampling technique in a study
        - Sample selection techniques, such as:
            - Simple random sampling
            - Stratified sampling
            - Cluster sampling
    - Level and confidence interval
        - The conceptualization of parameters and estimation
        - The central limit theorem
        - Levels of confidence and significance
        - Obtaining the margin of error for an experiment
        - Obtaining confidence intervals for a point estimate (interval estimation)
    - Sample size calculation
        - Determining the size of a sample, to ensure that it is representative of the population
        - Sample size calculation for finite and infinite quantitative variables

## Hypothesis tests

    - The application of a two-tailed parametric test
    - The execution of the hypothesis test steps
    - The rules for rejecting the null hypothesis of a test
    - To understand and calculate the p-value of a test
    - Applying a z-test with Python tools
    - t student distribution
    - Building and querying a t student table
    - The application of a one-tailed parametric test
    - Defining hypotheses and obtaining critical areas for a one-tailed test
    - Applying a t test with Python tools
    - The application of a comparison test between different sample means
    - The definition of hypotheses for tests between two samples
    - The application of a z test, for two samples, with Python tools
    - The chi-square distribution
    - To build and consult a chi-square table
    - The application of non-parametric chi-square test
    - The calculation of the p-value with the chi-square distribution
    - The application of non-parametric comparison tests between dependent samples
    - The elaboration of the non-parametric test of Wilcoxon
    - The application of non-parametric tests of comparison between independent samples
    - The elaboration of the non-parametric test of Mann-Whitney
    - The use of Python tooling for application of Wilcoxon and Mann-Whitney tests

## Correlation and regression

    - To obtain a matrix of covariance
    - The Pearson Correlation Coefficient
    - To get a correlation array
    - To interpret coefficients of covariance and correlation
    - The basic definitions of a simple linear regression
    - The ordinary squares method for obtaining the parameters of the model
    - To estimate the parameters with the use of the StatsModels Library Tooling
    - To calculate predictions inside and outside the sample

# Linear regression

## Testing relationships and predicting results

    - How to create a table with descriptive statistics of dataset data
    - How to Create a Correlation Matrix for Descriptive Statistics Table Data
    - Dependent variable behavior:
        - How to plot the dependent variable
        - How to import the seaborn library
        - How to create a dependent variable box-plot
        - How to create a two-variable box-plot
        - How to configure the styles and colors of the seaborn library
        - How to make a histogram with the dependent variable
    - Dependent vs explanatory variables
        - How to plot scatter plots between dataset variables with pairplot, jointplot and lmplot
    - Test and training datasets
        - How to prepare data and create training and test datasets
        - How to check the file sizes generated by the train_test_split function
        - How to estimate a linear regression model
        - How to get punctual forecasts
        - How to interpret the estimated coefficients
        - How to make graphical analysis of forecasts
    - Comparing models
        - How to estimate a new model, but this time using another explanatory  variable
        - How to create the new model's training and test datasets
        - How to compare the two models
        - Other regression metrics
        - Mean square error and its root
    - Saving and loading a model
        - How to save and load the estimated model using the pickle library

## Advanced modeling techniques

    - How to apply the logarithmic transformation to dataset data
    - How to perform the frequency distribution of the transformed dependent variable
    - F statistic and T statistic (Stats model)
    - How to plot the scatter plots between the transformed variables of the dataset
    - How to analyze the dispersion between the transformed variables
    - How to estimate the linear model using training data
    - How to obtain the coefficient of determination (R²) of the estimated model
    - Generating forecasts for model test data
    - How to obtain the coefficient of determination (R²) for model predictions
    - How to generate the model's point forecast
    - How to reverse the transformation to get the estimate in reais
    - How to create a simple simulator
    - How to obtain the model intercept
    - How to obtain the regression coefficients
    - How to create a DataFrame to store model coefficients
    - How to interpret the estimated coefficients
    - Graphically analyzing model results

## Statistical tests

    - Discover confidence interval with tconfint();
    - Describe our data statistically.
    - What it is, how to use it and when to use the Z Test and the T Test.
    - Generate a confidence interval for the averages of our distributions;
    - Use statsmodels `get_compare()`;
    - Compare means;
    - Compare different averages;
    - Use the normaltest;
    - Nonparametric test;
    - Use the ranksums.

# Analysis of experiments

    - How to Discern which sources are valid for data collection;
    - Define the objectives of the experiment, as well as identify the manipulable variables and the response of the experiment;
    - The importance of planning an experiment;
    - How to limit the area of experimentation;
    - Factorial planning.
    - Calculate the degrees of freedom of the residual;
    - Do the statistical significance analysis of the parameters of the model;
    - Build and interpret a normalized paret graph.
    - Propose new models to better represent the reality of an experiment;
    - Analyze a predicted chart by observing with the purpose of inferring the quality of the representativeness of a model;
    - Relate the R2 correlation coefficient with the quality of the adjustment and with the results presented by a graph of predicted by observed.
    - Use the adjusted model to obtain informations about the recipe;
    - Difference between statistical laws and mathematical laws;
    - Build and interpret color maps;
    - Insert lines on color maps to facilitate interpretation of results.

# Machine learning

    - Models of machine learning
        - Supervised learning
            - Binary classification
            Scikit:
            - Linear Support Vector Classification (Linear SVC)
            - Support Vector Classification (SVC)
            - Decision tree Classsifier
            - Dummy Classifier
            - Multinomial Naive Bayes
            - AdaBoost Classifier
            Multidimensional data:
                - Random Forest Classifier
                - Random Forest with SelectKBest
                - Evaluate results with Confusion Matrix
                - Random Forest with RFE (Recursive feature elimination)
                - Random Forest with RFECV (Cross-validation estimator)
                - Random Forest with PCA
                - Random Forest with TSNE
        - Unsupervised learning
            - K-Means
            - DBSCAN
            - Meanshift
            - Silhouette coefficient
            - Davies bouldin index calculation
            - Calinski Harabasz index calculation
            Validation:
                - Relative validation
                - Cluster structure validation
                - Cluster stability validation
