# jupyter-Tasks

  -Due: last commit on or before January 1st, 2021-

- Tasks assessment for Emerging Technologies Module in 2020.
- worth 50% of the marks for the module
- Tasks Completed in a single jupyter notebook.
- Repository synced with GitHub


 ## TASKS:

   Date Task given : October 5th, 2020
1. Python Function sqrt2
  (calculates and prints to the screen the square root of 2 to 100 decimal places)

   Date Task given : November 2nd, 2020
2. The Chi-Squared 
   (It is used to analyse whether two categorical variables are independent.)

   Date Task given : November 16th, 2020
 3.The standard deviation of an array of numbers x is
   (calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) )

  Date Task given : November 30th, 2020
4.Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set.
  (used to make predictions of species of iris.)





## Instructions for each task:

1.Write a Python function called sqrt2 that calculates and
  prints to the screen the square root of 2 to 100 decimal places. Your code should
  not depend on any module from the standard library1 or otherwise. You should
  research the task first and include references and a description of your algorithm.

2.The Chi-squared test for independence is a statistical
  hypothesis test like a t-test. It is used to analyse whether two categorical variables
  are independent. The Wikipedia article gives the table below as an example [4],
  stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats
  to verify this value and calculate the associated p value. You should include a short
  note with references justifying your analysis in a markdown cell.
  
3.November 16th, 2020: The standard deviation of an array of numbers x is
  calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .
  However, Microsoft Excel has two different versions of the standard deviation
  calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above
  calculation but in the STDEV.S calculation the division is by len(x)-1 rather
  than len(x) . Research these Excel functions, writing a note in a Markdown cell
  about the difference between them. Then use numpy to perform a simulation
  demonstrating that the STDEV.S calculation is a better estimate for the standard
  deviation of a population when performed on a sample. Note that part of this task
  is to figure out the terminology in the previous sentence.
  
4. November 30th, 2020: NB – when I first posted this task, I accidentally
  wrote “k-means” where I meant to write “kNN” for k Nearest Neighbours.
  Because of this, I will allow either algorithm to be used and have
  extended the deadline by two weeks. Use scikit-learn to apply k-means
  clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data
  set online. Explain in a Markdown cell how your code works and how accurate it
  might be, and then explain how your model could be used to make predictions of
  species of iris.
