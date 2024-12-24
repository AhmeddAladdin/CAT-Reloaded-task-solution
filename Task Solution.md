## CAT-Reloaded-task-solution
# Beginner level
------------------------------
## Question 1.

# 1. Define mean, median, and mode. Give a real-world example of when each would be the most appropriate measure of central tendency.

a) Mean : commonly known as the average value is defined as sum of all the values divided by the total number of values.

b) Median : is used when numerical data is sorted in some order and it is the midpoint of the set, making it more resistant to outliers than the mean.

c) Mode : on the other hand, highlights the value that is most frequently observed in the set of data.

*For Example in Real Estate:* 
- Mean: Real estate agents calculate the mean price of houses in a particular area so they can inform their clients of what they can expect to spend on a house.
- Median: Real estate agents also calculate the median price of houses to gain a better idea of the “typical” home price,
          since the median is less influenced by outliers (like multi-million dollar homes) compared to the mean.
- Mode: Real estate agents also calculate the mode of the number of bedrooms per house so they can inform their clients on how many bedrooms they can expect to have in houses in a particular area.

# -----------------------------------------------------------------------

# 2. Explain the concept of variance and standard deviation. How are they related?

i. Variance: The measure of how far the set of data is dispersed from their mean value

ii. Standard deviation : spread of the statistical data from the mean or average position

the relation is : standard deviation is the square root of variance.

# -----------------------------------------------------------------------

# 3. What do you know about Left and right skewness? And what happens to mean, median and mode in each case?

  Skewness is a way to describe the symmetry of a distribution.

i. A distribution is a *Right skewed* if it has a "Tail" on right side of the distribution. "Skewness is +ve"

ii. A distribution is a *Left skewed* if it has a "Tail" on left side of the distribution. "Skewness is -ve"

iii. skewness = 0 if the distribution is symmetric.

skewness = mean - mode

in right skewness : mean is bigger than median and mode, so skewness is +

in left skewness : mean is less than median and mode, so skewness is -

in case of mean = mode skewness is = 0

# -----------------------------------------------------------------------

# 4. What do you know about outliers? Give a real-world example demonstrating your understanding.

Outliers are a set of data points that are significantly different from the rest of the data in the group.
The difference is either much larger or much smaller than the others. This disrupts the data distribution and causes errors in data collection.
For example, in a dataset of monthly sales numbers, if the revenue for one month is much higher than the rest, identifying those high sales would be considered unusual.
Therefore, outliers distort results and indicate special or rare occurrences. Hence, they must be identified and removed.

# -----------------------------------------------------------------------

# 5. What’s the difference between population and sample? Do the same measurements (mean, mode, median) apply to both?

            population                                 VS.                         sample
The population includes all members of a specified group.  VS. A sample is a subset of the population.

Collecting data from an entire population can be time-consuming, expensive, and sometimes impractical or impossible. VS. Samples offer a more feasible approach to studying populations, allowing researchers to draw conclusions based on smaller, manageable datasets

Includes all residents in the city.  VS.  Consists of 1000 households, a subset of the entire population.
- yes, (mean, median, and mode) apply to both.
# ------------------------------------------------------------------------

# 6. What is the difference between a discrete and a continuous random variable?

                   discrete                                                    VS.                            continuous
They can take only specific or discrete values.                                VS. They can take any value within a specific range.

Discrete variables are typically measured on a nominal or ordinal scale.       VS. Continuous variables are typically measured on an interval or ratio scale.

Discrete variables are often represented by bar graphs or histograms.          VS. Continuous variables are often represented by line graphs or smooth curves.

Discrete variables have probability mass functions (PMF)                       VS. Continuous variables have probability density functions (PDF).

# ------------------------------------------------------------------------

# 7. What’s the difference between probability mass function and probability density function?

                   PMF                                                                VS.            PDF
The PMF is the probability that a discrete random variable takes at an exact value.   VS. The PDF is the probability that a continuous random variable takes at a specified interval.

The PMF deals with the discrete random variables.                                     VS. The PDF deals with the continuous random variables.

PMF is evaluated at specific point.                                                   VS. PDF is evaluated at specified interval

# ------------------------------------------------------------------------

# 8. In normal distribution, what is the percentage of data falls within two standard deviations of the mean?
- Due to Empirical : the percentage of data falls within two standard deviations of the mean = *95%*

# ------------------------------------------------------------------------
# ------------------------------------------------------------------------

## Question 2:

# i. For this sample, estimate mean, median, mode, variance and standard deviation.
- mean = (3+3+2+1+1+4+1+1+2+2)/10 = 2
- median => data after sorting = [1, 1, 1, 1, 2, 2, 2, 3, 3, 4]

   mid integers = 2, 2  

   median = (2 + 2)/2 = 2
- mode = 1
- variance = sum(x-mean)^2/n-1 = 10/9 = 1.111
- std deviation = sqrt(variance) = 1.0541

# ii. Demonstrate how it will differ if it was the whole population.
it will differ only in variance and std deviation
- variance = sum(x-mean)^2/n = 1
- std deviation = sqrt(variance) = 1

# ------------------------------------------------------------------------
# ------------------------------------------------------------------------

## Question 3:

- What do you say about the distribution of this sample? How it will affect the mean, median and mode?
the distribution is left skewed "tail in left or negative direction",, Mode > Median > Mean ,, mean is more affected than other, median is less sensitive.

# ------------------------------------------------------------------------
# ------------------------------------------------------------------------

## Question 4:

1. What do you know about Python’s containers?
- List: list items are enclosed in [] ,, list can have different data types ,, it's ordered, use index to access item ,, list items are not unique ,, list are mutable => Replace, Delete, Edit
- Set: set items are enclosed in {} ,, set is not ordered or indexed ,, can only contain immutable data types, can't contain lists ,, set items is unique
- Tuple: Items are enclosed in () ,, can remove () if you want ,, tuple are ordered, can use index ,, can't be edited ,, items aren't unique ,, can have any type of data
- Dictionary : Dict. items are enclosed in curly bracts {} ,, Dict. items are contain key : value ,, Dict. key need to be an immutable ->(strings, numbers, tuple), list not allowed ,, Dict. value can be any type of data ,, Dict. key need to be unique ,, Dict. isn't ordered, can access its element with key

2. What does apply() method do?
like for loop, we use it to do a specific function to each element within the data.

3. How would you reverse a list in python in one line? (Don’t use reverse() method).
print(lst[::-1])

4. Compare between continue, break and pass.
- break: when a certain condition is true, and you want to end the loop now, "break" exit the loop.
- continue: when you want to skip the rest of the code and go to the next iteration, "continue" skip the rest of the code.
- pass: do nothing, it's a placeholder make the code looks correct.

5. What is the output of this code?
=> [1, 2, 3, 4, 5]

6. What is the output of this function?
[1] [1 1] [1 1 1]

7. What do you know about Object Oriented Programming?


8. What do you know about Functional Programming?



















