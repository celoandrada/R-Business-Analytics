# Data Exploration

This section focuses on exploring datasets before building models.

Concepts covered:

- Summary statistics
- Missing value detection
- Variable identification
- Mean, median, minimum, maximum
- Histograms
- Boxplots
- Scatterplots
- Understanding categorical vs continuous variables

Example datasets used:

- House dataset
- NBA dataset

## Coursework Examples

### House Dataset
Used R to inspect a housing dataset by checking:

- Number of observations and variables
- Missing values
- Categorical vs continuous variables
- Mean and median
- Minimum and maximum
- Summary statistics
- Outliers using boxplots

### NBA Dataset
Used R to explore player salary and performance variables before regression modeling.

## R Concepts Practiced

```r
summary(house)
str(house)
colSums(is.na(house))
mean(house$value)
median(house$value)
min(house$tax)
max(house$tax)
hist(house$bedroom)
boxplot(house$value)
```

Before building models, I learned how to check whether a dataset is clean, understand variable types, identify missing values, and use visualizations to spot patterns or outliers.
