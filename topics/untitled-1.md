# Data Processing

[Introduction to Numpy -1 : An absolute beginners guide to Machine Learning and Data science.](https://hackernoon.com/introduction-to-numpy-1-an-absolute-beginners-guide-to-machine-learning-and-data-science-5d87f13f0d51)

[How to Index, Slice and Reshape NumPy Arrays for Machine Learning in Python](https://machinelearningmastery.com/index-slice-reshape-numpy-arrays-machine-learning-python/)

[Intro to Pandas: -1 : An absolute beginners guide to Machine Learning and Data science.](https://hackernoon.com/intro-to-pandas-1-an-absolute-beginners-guide-to-machine-learning-and-data-science-a1fed3a6f0f3)

[Pandas tips and tricks – Towards Data Science](https://towardsdatascience.com/pandas-tips-and-tricks-33bcc8a40bb9)



### Select Data

Data can be selected from Pandas DataFrame using:

* Square brackets
* the `loc` method
  * label-based \(i.e. using the labels of columns and observations\)
  * inclusive
* the `iloc` method
  * position-based \(i.e. using the index of columns and observations\)
  * exclusive

Examples:

```python
# Print out country column as Pandas Series
print(cars['country'])​

# Print out country column as Pandas DataFrame
print(cars[['country']]) 

# Print out DataFrame with country and drives_right columns
print(cars[['country','drives_right']])

​# Print out first 3 observations
print(cars[:3]) ​

# Print out fourth, fifth and sixth observation
print(cars[3:6])

​# Print out drives_right column as Series
print(cars.loc[:, 'drives_right'])​

# Print out drives_right column as DataFrame
print(cars.loc[:,['drives_right']])​

# Print out cars_per_cap and drives_right as DataFrame
print(cars.loc[:,['cars_per_cap','drives_right']])
```

The `loc` and `iloc` method are more powerful but square brackets are good enough for selecting all observations of some columns.

### 

