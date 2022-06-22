# Project Overview



* The Challenge
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

# Data

The dataset for this project is from kaggle's advanced housing price prediction v9. This can be found at: https://www.kaggle.com/competitions/titanic/data

# Tools Overview
The following are the tools that are covered in the notebooks. They are popular tools that machine learning engineers and data scientists need in one way or another and day to day.

Python is a high level programming language that has got a lot of popularity in the data community and with the rapid growth of the libraries and frameworks, this is a right programming language to do ML.

NumPy is a scientific computing tool used for array or matrix operations.

Pandas is a great and simple tool for analyzing and manipulating data from a variety of different sources.

Matplotlib is a comprehensive data visualization tool used to create static, animated, and interactive visualizations in Python.

Scikit-Learn: Instead of building machine learning models from scratch, Scikit-Learn makes it easy to use classical models in a few lines of code. This tool is adapted by almost the whole of the ML community and industries, from the startups to the big techs.

OBSERVATIONS:

1) By taking a look at the data description, I observed that it would be better to add the SibSp and Parch variables and I was right. The new RelativesOnBoard variable has more feature importance that the SibSp and Parch variable.

2) Also I decided to split the ages into AgeBucket and turn the resulting variable to a categorical variable as it makes more sense.


#  Project Steps

1. Loading The Data
2. Data Wrangling and Exploratory Data Analysis
3. Building Pipelines For Data Preprocessing 
4. Feature Selection
5. Model Selection And Evaluation
6. Hyperparameter Tuning
7. Inference




