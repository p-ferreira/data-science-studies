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
