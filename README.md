# fundaw23
**Project and tasks for Fundamentals of Data Analytics W2023 ATUGM**
Author: Nur Bujang

## List of Contents

### TASKS
1. Task 1
    - Description
    - Method
    - Conclusion
    - References

2. Task 2
    - Description
    - Method
    - Conclusion
    - References

3. Task 3
    - Description
    - Method
    - Conclusion
    - References

4. Task 4
    - Description
    - Method
    - Conclusion
    - References

5. Task 5
    - Description
    - Method
    - Conclusion
    - References
      
## PROJECT: Analysis of Iris Flower Data Set by Ronald A. Fisher
    - Description
    - Method
    - Conclusion
    - References

## **Task 1 : Collatz Conjecture**
The Collatz conjecture is a famous unsolved problem in mathematics. The problem is to prove that if you start with any positive integer x and  repeatedly apply the function f ( x ) below, you al ways get stuck in the repeating sequence 1, 4, 2, 1, 4, 2, . . .

\begin{align*}
f(x) = \begin{cases} 
    x \div 2 & \text{if } x \text{ is even} \\
    3x + 1 & \text{if } x \text{ is odd}
\end{cases}
\end{align*}

For example, starting with the value 10, which is an even number, we divide it by 2 to get 5. Then 5 is an odd number so, we multiply by 3 and add 1 to get 16. Then we repeatedly divide by 2 to get 8, 4, 2, 1. **Once we are at 1, we go back to 4 and get stuck in the repeating sequence 4, 2, 1 as we suspected.**

### Task Description:
The task is to verify, using Python, that the Collatz conjecture is true for the first 10000 positive integers.

### Method:
1. Based on further readings, according to the Collatz Conjecture, all numbers will end with 1 before going into another loop of 4,2,1 (1-3).
2. Hence, the strategy is to stop the While loop at 1 (4).
3. For Task 1 markdown, the Collatx Conjecture formula was written in LaTex (5).
4. I used Python Functions (6) and While loop (4) for the conditions on odd and even numbers. Python list append method was used to keep adding on to the list until it reaches 1 (7).
5. Python For Loop For i in Range was used (8) to determine the limit, with if, else conditions (9, 10) to verify that the last number in the list (11) is 1.
6. Lastly, I called the verify_collatz function and printed out the verification/nonverification statement.

### Conclusion:
The Collatz Conjecture is verified to be true for the first 10000 positive integers.

### References:
1. Honner, P. (2020). The Simple Math Problem We Still Can’t Solve. [online] Quanta Magazine. Available at: https://www.quantamagazine.org/why-mathematicians-still-cant-solve-the-collatz-conjecture-20200922/ [Accessed 13 Oct. 2023].
2. ‌Stack Overflow. (n.d.). Collatz Sequence. (Python 3). [online] Available at: https://stackoverflow.com/questions/33324432/collatz-sequence-python-3#33324464 [Accessed 15 Oct. 2023].
3. Sao, P. (2021). Understanding Collatz Sequence in Python. [online] Python Pool. Available at: https://www.pythonpool.com/collatz-sequence-python/ [Accessed 15 Oct. 2023]. 
4. w3schools (n.d.). Python While Loops. [online] www.w3schools.com. Available at: https://www.w3schools.com/python/python_while_loops.asp [Accessed 17 Oct. 2023].
5. www.overleaf.com. (n.d.). Mathematical expressions. [online] Available at: https://www.overleaf.com/learn/latex/mathematical_expressions [Accessed 17 Oct. 2023].
6. W3 Schools (2019). Python Functions. [online] W3schools.com. Available at: https://www.w3schools.com/python/python_functions.asp [Accessed 17 Oct. 2023].
7. www.w3schools.com. (n.d.). Python List append() Method. [online] Available at: https://www.w3schools.com/python/ref_list_append.asp [Accessed 17 Oct. 2023].
8. ‌Thompson, J.L. (2021). Python For Loop - For i in Range Example. [online] freeCodeCamp.org. Available at: https://www.freecodecamp.org/news/python-for-loop-for-i-in-range-example/ [Accessed 17 Oct. 2023].
9. W3Schools (2019). Python Conditions. [online] W3schools.com. Available at: https://www.w3schools.com/python/python_conditions.asp [Accessed 17 Oct. 2023].
10. ‌GeeksforGeeks. (2017). Python if else. [online] Available at: https://www.geeksforgeeks.org/python-if-else/ [Accessed 17 Oct. 2023].
11. Stack Overflow. (n.d.). Meaning of list[-1] in Python. [online] Available at: https://stackoverflow.com/questions/52395099/meaning-of-list-1-in-python [Accessed 15 Oct. 2023].

## **Task 2 : Penguins Data Set Variables**
Give an overview of the famous penguins data set (1,2) and explain the types of variables it contains. 

### Task Description: 
The task is to suggest the types of variables that should be used to model them in Python and to explain your rationale.

### Method:
1. First, I imported the numpy library for computational operations and pandas library for data processing.
2. After importing the penguins.csv data set (3), I ran df.head to show a few lines of the data frame.
3. To find out the variable types (4), I performed df.dtypes (5-6) but it can also be achieved using df.info (7).
4.  The output showed that the data frame consists of columns containing objects and floats. However, a quick lookover of the data file shows that the flipper length and body mass are int values. My question was why did these columns output as floats.
5.  I checked each numerical column by row using df.at (8) and isinstance function (9) to confirm that these column variables are not int values. 
6.  Then I used For loops (10) and df.astype (11) and pandas categorical data (12-13) to print out the categories of columns with string values.
7.  For the numerical columns, I used a For loop (10), exception handling (14-16), and df.astype (11) to confirm that these are all floats by confirming that these cannot be converted into integers. The flipper length and body mass are considered floats because they contain null values (17) which cannot be converted into int values. df.info (7) would also give the same information in terms of null values.
‌
### Conclusion:
The penguins dataset consists of object columns containing strings and numerical columns containing floats. Even though flipper length and body mass columns are int values on the data file, these are considered floats because they contain null values.

### References:
1. Waskom, M. (2022). seaborn-data. [online] GitHub. Available at: https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv [Accessed 13 Oct. 2023].
2. Pandey, P. (2020). penguin dataset : The new Iris. [online] kaggle.com. Available at: https://www.kaggle.com/code/parulpandey/penguin-dataset-the-new-iris [Accessed 17 Oct. 2023].
3. datatofish.com. (2023). How to Import a CSV File into Python using Pandas - Data to Fish. [online] Available at: https://datatofish.com/import-csv-file-python-using-pandas/ [Accessed 20 Oct. 2023].
4. Polamuri, S. (2023). Mastering Data Analysis: A Comprehensive Look at Continuous and Categorical Data Types - Dataaspirant. [online] https://dataaspirant.com/. Available at: https://dataaspirant.com/continuous-and-categorical-data-types/ [Accessed 20 Oct. 2023].
5. pandas.pydata.org. (n.d.). pandas.DataFrame.dtypes — pandas 1.5.1 documentation. [online] Available at: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dtypes.html [Accessed 20 Oct. 2023].
6. note.nkmk.me. (2023). pandas: How to use astype() to cast dtype of DataFrame | note.nkmk.me. [online] Available at: https://note.nkmk.me/en/python-pandas-dtype-astype/ [Accessed 20 Oct. 2023].
7. w3resource. (2022). Pandas DataFrame: - info() function. [online] Available at: https://www.w3resource.com/pandas/dataframe/dataframe-info.php [Accessed 20 Oct. 2023].
8. w3resource. (2022a). Pandas DataFrame property: at. [online] Available at: https://www.w3resource.com/pandas/dataframe/dataframe-at.php [Accessed 20 Oct. 2023].
9. www.w3schools.com. (n.d.). Python isinstance() Function. [online] Available at: https://www.w3schools.com/python/ref_func_isinstance.asp [Accessed 22 Oct. 2023].
10. W3Schools (2019). Python For Loops. [online] W3schools.com. Available at: https://www.w3schools.com/python/python_for_loops.asp [Accessed 22 Oct. 2023].
11. pandas.pydata.org. (n.d.). pandas.to_numeric — pandas 1.4.2 documentation. [online] Available at: https://pandas.pydata.org/docs/reference/api/pandas.to_numeric.html [Accessed 21 Oct. 2023].
12. pandas.pydata.org. (n.d.). Categorical data — pandas 1.5.0 documentation. [online] Available at: https://pandas.pydata.org/docs/user_guide/categorical.html [Accessed 21 Oct. 2023].
13. pandas.pydata.org. (n.d.). pandas.Series.cat.ordered — pandas 2.1.1 documentation. [online] Available at: https://pandas.pydata.org/docs/reference/api/pandas.Series.cat.ordered.html [Accessed 21 Oct. 2023].
14. Satyam, K. (2020). Try, Except, else and Finally in Python. [online] GeeksforGeeks. Available at: https://www.geeksforgeeks.org/try-except-else-and-finally-in-python/ [Accessed 21 Oct. 2023].
15. Python Tutorial - Master Python Programming For Beginners from Scratch. (n.d.). Understanding the Python try...except...finally Statement. [online] Available at: https://www.pythontutorial.net/python-basics/python-try-except-finally/ [Accessed 21 Oct. 2023].
16. van de Klundert, S. (n.d.). Python Exceptions: An Introduction – Real Python. [online] realpython.com. Available at: https://realpython.com/python-exceptions/ [Accessed 21 Oct. 2023].
17. pandas.pydata.org. (n.d.). pandas.isnull — pandas 1.4.2 documentation. [online] Available at: https://pandas.pydata.org/docs/reference/api/pandas.isnull.html [Accessed 21 Oct. 2023].
‌
## **Task 3 : Penguins Data Set Distribution Model** 
For each of the variables in the penguins data set(1):

### Task Description:
The task is to suggest what probability distribution from the numpy random distributions list is the most appropriate to model the variable (2).

### Method:
1. 
2.

### Conclusion:
The 

### References:
1. Waskom, M. (2022). seaborn-data. [online] GitHub. Available at: https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv [Accessed 13 Oct. 2023].  
2. numpy.org. (n.d.). Random Generator — NumPy v1.21 Manual. [online] Available at: https://numpy.org/doc/stable/reference/random/generator.html [Accessed 4 Nov. 2023].
w3 random dist: www.w3schools.com. (n.d.). Random Data Distribution. [online] Available at: https://www.w3schools.com/python/numpy/numpy_random_distribution.asp [Accessed 4 Nov. 2023].
df.info: w3resource. (2022). Pandas DataFrame: - info() function. [online] Available at: https://www.w3resource.com/pandas/dataframe/dataframe-info.php [Accessed 4 Nov. 2023].
x2: numpy.org. (n.d.). numpy.random.Generator.noncentral_chisquare — NumPy v1.26 Manual. [online] Available at: https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.noncentral_chisquare.html [Accessed 5 Nov. 2023].
scipy: docs.scipy.org. (n.d.). scipy.stats.goodness_of_fit — SciPy v1.11.3 Manual. [online] Available at: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.goodness_of_fit.html [Accessed 5 Nov. 2023].
hypo testing: www.w3schools.com. (n.d.). Statistics - Hypothesis Testing a Mean. [online] Available at: https://www.w3schools.com/statistics/statistics_hypothesis_testing_mean.php [Accessed 6 Nov. 2023].
lognorm: docs.scipy.org. (n.d.). scipy.stats.lognorm — SciPy v1.10.0 Manual. [online] Available at: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.lognorm.html [Accessed 6 Nov. 2023].
gamma: docs.scipy.org. (n.d.). scipy.stats.gamma — SciPy v1.11.3 Manual. [online] Available at: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.gamma.html#scipy.stats.gamma [Accessed 6 Nov. 2023].
skewnorm: docs.scipy.org. (n.d.). scipy.stats.skewnorm — SciPy v1.11.2 Manual. [online] Available at: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.skewnorm.html [Accessed 6 Nov. 2023].

## **Task 4 : Head Probability** 
Suppose you are flipping two coins, each with a probability p of giving heads.

### Task Description:
The task is to plot the entropy of the total number of heads versus p.

 
### Method:
1. 
2. 

### Conclusion:
The 

### References:
1. 
2. 
3. 
4. 
5. 
6. 
7. 
8. 

## **Task 5 : Penguins Data Set Plots** 
Penguins data set.

### Task Description:
The task is to create an appropriate individual plot for each of the variables in the penguin data set (1)


### Method:
1. 
2. 

### Conclusion:
The.

### References:
1. Waskom, M. (2022). seaborn-data. [online] GitHub. Available at: https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv [Accessed 13 Oct. 2023].  
2. 
3. 
4. 
5. 
6. 
7. 
8. 
9. 
10. 

# PROJECT : Analysis of Iris Flower Data Set by Ronald A. Fisher

## Description
The project is to create a notebook investigating the variables and data points within the well-known iris flower data set associated with Ronald A Fisher.(1)

In the notebook, you should discuss the classification of each variable within the data set according to common variable types and scales of measurement in mathematics, statistics, and Python.

Select, demonstrate, and explain the most appropriate summary statistics to describe each variable.

Select, demonstrate, and explain the most appropriate plot(s) for each variable.

The notebook should follow a cohesive narrative about the data set.

## Method


## Conclusion


## References
import csv file: datatofish.com. (2023). How to Import a CSV File into Python using Pandas - Data to Fish. [online] Available at: https://datatofish.com/import-csv-file-python-using-pandas/ [Accessed 20 Oct. 2023].
‌
df.info: w3resource. (2022). Pandas DataFrame: - info() function. [online] Available at: https://www.w3resource.com/pandas/dataframe/dataframe-info.php [Accessed 20 Oct. 2023].
‌
‌
