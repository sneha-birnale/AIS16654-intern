Task 1 -
 #variable selection rules -
We studied the variable selection rules in python .
 #Operators -
We studied the operatos in python i.e Arithmatic , logical, assignment , identity,bitwise, membership,comparison etc .
 #data types -
 we studied different data types in python like lists,tuple, set,dictionary .
 In list we study the list methods like append, copy,reverse,pop,count,index,sort,accessing etc .
 Tuples are immutable which means values in tuple cannot be modified ,so we study the how declare the the tuples .
 In set we studied the methods like mutable , ordered etc 
  dictionary contains key value pairs as its data elements . They are mutable .
  #numbers -
 There are three types of numbers i.e numeric,float,complex .
  #strings-
In strings we studied sinle line and multi line string ,strings are written  in double  quotes.

Task 2 -
#if statement -
 if statement is used when single condition is to check like number is equal to , not equal to,greater than , smaller than etc.
#if else statement -
if ele statement is used to check the two conditions like positive negative , numeric complex etc 
#if  elif else statement -
 if elif else statement is used to check more than two conditions .
#for loop -
for loop is used to execute the code in certain number of times over a range or a sequence .
#while loop -
while loop is used to execute the code in certain number of times over a particular condition ,while loop continues untill a particular condition is no longer met .

Task 3 -
In Task 3 we study Breck,pass,continuenstatement also we study User define function like statistical(mean,median,mode,variance) and logical(odd,even,grades)
#break-
Functionality: When break is encountered inside a loop, the loop stops its execution and control is transferred to the statement immediately following the loop.
Use Case: It is useful when you want to exit a loop as soon as a certain condition is met, avoiding unnecessary iterations.
#continue
Functionality: When continue is encountered, the current iteration is terminated, and the loop proceeds with the next iteration.
Use Case: It is useful when you want to skip over some parts of the loop but continue with the next iterations. For instance, you might want to skip over even
numbers or any specific condition within a loop.
#pass
Functionality: The pass statement does nothing and is used as a placeholder.
Use Case: It is useful when a statement is syntactically required, but you do not want any action to be taken. Commonly used during development as a placeholder for future code,
in empty function or class definitions, or within conditional statements where you plan to add code later.
#Statistical User-Defined Functions-
Statistical functions are essential for data analysis and help summarize and understand the data's properties.
Mean is use to Calculate the average of a list of numbers.median is use to Find the middle value of a list of numbers.mode is used to Find the most frequently occurring value(s)
in a list of numbers.Variance is used to Measure the spread of numbers in a list from the mean.Standard Deviation is used to Measure the amount of variation or dispersion of a set
of values.Percentile is used to Determine the value below which a given percentage of observations fall.range is used to Calculate the difference between the maximum and minimum
values in a list.Interquartile Range (IQR) is used to Measure the middle 50% of the data.Covariance is used to Measure how two variables change together.Correlation Coefficientis used to Measure the strength and direction of the relationship between two variables.
#Logical User-Defined Functions-
#is_even-Purpose: Check if a number is even.#is_odd-Purpose: Check if a number is odd.#is_prime-Purpose: Check if a number is prime.#is_palindrome-Purpose: Check if a string is a palindrome.#is_anagram-Purpose: Check if two strings are anagrams.#is_subset-Purpose: Check if one set is a subset of another.#is_superset-Purpose: Check if one set is a superset of another.#are_disjoint-Purpose: Check if two sets are disjoint.#are_equal-Purpose: Check if two lists are equal.#is_sorted-Purpose: Check if a list is sorted.

 Task 4 -
#In task 4 we studied all about Numpy library.Starting with a basic introduction and ends up with creating and plotting random data sets,
and working with NumPy functions:
#NumPy is an open source project that enables numerical computing with Python. It was created in 2005 building on the early work of the Numeric and Numarray libraries.
NumPy will always be 100% open source software and free for all to use.
We studied  1) creating arrays, 2)array indexing ,3) slicing, 4)numpy data types ,5) copy or view, 6)array shape and reshape ,7)array itterating , 8)join , split, search , sort and filter .
Here 1D array , 2D array,3D array and multidimensional array are studied.
NumPy has some extra data types, and refer to data types with one character, like i for integers, u for unsigned integers etc.
Below is a list of all data types in NumPy and the characters used to represent them.
1)i - integer 
2)b - boolean
3)u - unsigned integer
4)f - float
5)c - complex float
6)m - timedelta
7)M - datetime
8)O - object
9)S - string
10)U - unicode string
11)V - fixed chunk of memory for other type ( void ) 
#Then we learn how to  generate Random Number.
NumPy offers the random module to work with random numbers.
#Data Distribution is a list of all possible values, and how often each value occurs.
Such lists are important when working with statistics and data science.
The random module offer methods that returns randomly generated data distributions. 
Then we see that generation of random numbers from particular distribution and visuallisation of that distribution .like normal distribution ,binomial, poisson , uniform, logistic, multinomial, exonential, chi-square,rayleighs,pareto,zipf distributions
To plot the graph of distribution
#from numpy import random
#import matplotlib.pyplot as plt
#import seaborn as sns
Then we use ufuncs stands for "Universal Functions" and they are NumPy functions that operate on the ndarray object.
We studied ufunctions like simple arithmatic , rounding decimals, logs, summations, products, differences, finding lcm,gcd, trignometric functions, hyperbolic function and set operations.

Task 5 -
In task 5 we studied the pandas library in python.
#we see creation of series and their operation .A Pandas Series is like a column in a table. It is a one-dimensional array holding data of any type.
#Then we see the data frame creation using dictionary and matrix ,and how to to read data in csv and xlsx file in panda library in python. 
#Data frame operation -
In data frame operation different methods of operation like value count , apply, unique, nunique,describe,merge,sort etc
#selection-
In selection we see that how to select data frame column and row by using (loc,iloc) function . 
#In pandas, selecting data from a DataFrame involves specifying which columns and/or rows you want to work with. 
#we can use several methods for selection, including .loc, .iloc, and boolean indexing. 
 Also conditional selection with how to add , delete and update column in the data frame .Also seen that indexing and removing indexing by set reset function.
 Operation between two columns like addition , substraction, multiplication and division are carried out .
#missing values
In missing values we studied checking missing values, how to drop missing values by row and by column and also filling missing values by mean ,median etc.By using function
#Using isnull(): This method returns a DataFrame of the same shape with boolean values indicating whether the data is missing (True) or not (False).
#we can drop rows that contain any missing values using dropna(axis=0):
#we can fill missing values with a specific value using fillna(value):
 
 Task 6 - 
 In task 6 we studied the matplotlib and seaborn library.
 Matplotlib is a graph plotting library in python that serves as a visualization utility.
 #Pyplot
Most of the Matplotlib utilities lies under the pyplot submodule, and are usually imported under the plt alias:
#import matplotlib.pyplot as plt
#Plotting x and y points
The plot() function is used to draw points (markers) in a diagram.
In matplotlib we study matplotlib plotting with markers,lines,labels,grid,subplot,scatter plot,bars, histograms and pie charts .
#seaborn libraray-
Seaborn is a powerful and versatile data visualization library in Python, built on top of the popular Matplotlib library. 
It provides a high-level interface for drawing attractive and informative statistical graphics. 
Seaborn is particularly useful for visualizing complex datasets and for creating aesthetically pleasing visualizations with minimal code.
#import seaborn as sns
#In seaborn library we see different types of plotting of graphs such as distribution plot, box plot, violin plot, bar plot,scatter pot, 
line plot, heatmap, pair plot ,facet grid, regression plot , residual plot. 
 
Task 7-
#1] Numpy exercise:- solved problems related to array indexing slicing,creating arrays containg zeros ones generating random numbers from normal distribution,
using linspace addition of elements in an array calculate mean standard deviation, etc
#2]Ecommerce purchase exercise:- studied the how to read the file and found out the mean purchase price maximum and minimum purchase price,number of people having job title lawyer number of people making the purchase during the AM and how many people made the purchase during PM,5 most common Job Titles,person with the following Credit Card Number: 4926535242672853 ,number of people have American Express as their Credit Card Provider and made a purchase above $95,number of people have a credit card that expires in 2025,top 5 most popular email providers/hosts (e.g. gmail.com, yahoo.com, etc...)
#3] Salary exercise:-studied the data read the file and found out average BasePay,the highest amount of OvertimePay in the dataset,job title of JOSEPH DRISCOLL, How much does JOSEPH DRISCOLL make,name of highest paid person,name of lowest paid person,the average (mean) BasePay of all employees per year,number of unique job titles,the top 5 most common jobs,number of  Job Titles were represented by only one person in 2013, people have the word Chief in their job title,there a correlation between length of the Job Title string and Salary.

#Case study -
In this case study we download the titanic data from kaggle and import it to jupyter notebook.Then we find the missing values and filled the missing values by its mean ,and droped the variable like cabin,passenger id etc. Then we do label encoding for the categorical variable.
Then Performd the EDA i.e exploratory data analysis on titanic data such as bar plot,scatter plot,joint plot and pie chart .
From the graph it is seen that the females are survived more than males.The passengers who are in class 1st are most survived as compared to class 2nd and 3rd.
In titanic data survival is the dependent variable and other variables like age,sex,fare,sibps,embarked are independent variables.
Then we split data into train test and fit the algorithms like naive bayes,KNN, dicision tree and predict the text data using particular fitted model.
In model evaluation we find accuracy,classification report,confusion matrix,precision and recall for each algorithm .and compare it with each other and we may conclude that 
decision tree is the best model on the basis of prcision , accuracy and recall, Where the values of precision,accuracy and recall for dicision tree are high as compared to knn and naive bayes.

#Dashboard-
In this task we created a dashoard on project data i.e Bike sharing demand data in power bi dashboard.We download the Bike sharing demand data from kaggle. In power bi we get the data from csv file then by using graphs ,sclicers,card and other features we create a dashoard in power bi.

#Project-
1)Objectives -
#To identify and evaluate the seasonal fluctuations in the demand for rental bike.
#Investigate the variations in bike rental demand across different hours per day and days of the month and to identify the peak demand periods.
#To identify which features in dataset have the most significant impact on target outcome
#To determine which model is best suited for bike sharing demand dataset.
2)EDA and model building-
In the bike sharing demand data prediction project we download the data from kaggle and import it to jupyter notebook then perform EDA on the data.
To identify and evaluate the seasonal fluctuations in the demand for rental bike.
Then we cleaned data by handling missing values and outliers to build the various models like - linear regression,ridge regression,elastic net, random forest, decision tree,KNN,SVR9Support vector regressor),PCR(principal component regbressor),PLSR(partial least square regressor),Gradient Boosting and find the root mean square error and R square for all the 10 models.
Then we perform grid search cv on 10 models to find the best parameter once we find the Best parameters then again we build the 10 models with that best parameter, and find the RMSE and R square values after the grid search cv .
Also we find feature importance from decision tree model and find the best parameter i.e Hour , tempreture,solar radiation,humidity,seasons and holiday and fit the all 10 models with these 6 variables.and find the RMSE and R square of all models.
Then plot the bar graphs and joint bar plots of rmse values and r square values. Also compare the rmse and R square values of before and after grid search cv .
3)Conclusion-
1. Seasonal Trends: Bike-sharing demand typically varies with the season, with higher usage in warmer months and lower usage in colder months.
2. Weather Impact: Weather conditions such as temperature, humidity significantly influence bike-sharing demand. Favorable weather conditions usually correlate with increased bike usage.
3. Impact of Holidays: Holidays tend to disrupt regular usage patterns, often resulting in lower demand.
4.Based on rmse and r square ,the best performing models are random forest and gradient boosting.
5. By feature importance the variables like hour, tempreture, humidity, solar radiation, Functioning day and seasons are important impact on bike sharing demand.













