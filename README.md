# AutoML-data-munging-assignment
In this assignment, I wrote a function in python to manipulate dates and time values in python, and 2nd question is to write a general function to remove variables in a dataset with pearson correlation >=0.85, so as to deal with multicollinearity effectively.

Questions:
1) Write a function to identify dates columns and manipulate those columns and create new columns which are difference of other 2 date columns. Print out the data in google colab:

Thing to consider

· Date column might have some invalid entries in them
· Date can be of different format throughout the column
· Code should be efficient and fast
· Code should be well commented and easy to interpret
· Code should be robust enough to run on any dataset
· Make a dummy dataset by yourself.

2) Write a function in python that take dataframe as input and drop columns having Pearson correlation more than 0.85

Thing to consider
· Code should drop least amount of variable as possible. (this is an important point)
· Code should be efficient and fast
· Code should be well commented and easy to interpret
· Code should be robust enough to run on any dataset
· Make a dummy dataset by yourself or pass any publicly available dataset to test out your logic
