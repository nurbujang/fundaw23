# fundaw23
**Project and tasks for Fundamentals of Data Analytics W2023 ATUGM**
Author: Nur Bujang

## TASKS
### List of Contents
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
### Description
### Method
### Conclusion
### References


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

‌## **Task 2 : Penguins Data Set Description** 
Give an overview of the famous penguins data set (1) and explain the types of variables it contains. 

### Task Description: 
The task is to suggest the types of variables that should be used to model them in Python and to explain your rationale.

### Method:
1. Waskom, M. (2022). seaborn-data. [online] GitHub. Available at: https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv [Accessed 13 Oct. 2023].
2. Pandey, P. (2020). penguin dataset : The new Iris. [online] kaggle.com. Available at: https://www.kaggle.com/code/parulpandey/penguin-dataset-the-new-iris [Accessed 17 Oct. 2023].

‌
### Conclusion:
The

### References:
1. 
2. 


## **Task 3 : Penguins Data Set Distribution Model** 
For each of the variables in the penguins data set():

### Task Description:
The task is to suggest what probability distribution from the numpy random distributions list is the most appropriate to model the variable ().


### Method:
1. 
2.

### Conclusion:
The 

### References:
1. () Waskom, M. (2022). seaborn-data. [online] GitHub. Available at: https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv [Accessed 13 Oct. 2023].  
2. numpy.org. (n.d.). Random Generator — NumPy v1.21 Manual. [online] Available at: https://numpy.org/doc/stable/reference/random/generator.html [Accessed 13 Oct. 2023].
3. 
4. 
5. 

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
The task is to create an appropriate individual plot for each of the variables in the penguin data set ()


### Method:
1. 
2. 

### Conclusion:
The.

### References:
1. () Waskom, M. (2022). seaborn-data. [online] GitHub. Available at: https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv [Accessed 13 Oct. 2023].  
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
1. archive.ics.uci.edu. (1988). UCI Machine Learning Repository. [online] Available at: https://archive.ics.uci.edu/dataset/53/iris [Accessed 14 Oct. 2023].
‌