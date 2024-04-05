# EDA-Prima-Indian-Diabetes

## Background:
Diabetes is one of the most frequent diseases worldwide, and the number of diabetic patients has grown over the years. The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes. A few years ago, research was done on a tribe in America called the Pima tribe (also known as the Pima Indians). In this tribe, it was found that the ladies were prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients were females at least 21 years old of Pima Indian heritage. 

## Objective:
In this project, I have analyzed different aspects of Diabetes in the Pima Indian tribe by doing Exploratory Data Analysis (univariate, bivariate).

## Summary of observations:
(1) In this EDA, I have used Python packages such as Numpy, Pandas, Matplotlib, and Seaborn. Numpy, also known as 'Numerical Python', is a Python library used for arrays. Pandas, also known as 'Panel data,', is a software library for the Python programming language. Pandas are used for data cleaning, data transformation, data manipulation, data visualization, and data analysis. Matplotlib is a data visualization library in python used for plotting graphs. Seaborn is a data visualization library in Python based on Matplotlib. Seabon is useful for visualizing univariate and bivariate data.

(2) There are no missing values in the Pima dataset.

(3) Summary statistics of the data represent the overall quantitative summary statistics for all variables of the dataset. It computes the total number of data points, mean, standard deviation, minimum and maximum values, 1st,2nd(median), and 3rd quartiles for each column of the dataset. For example, if we consider the BMI column from the dataset, there are 768 data points with a mean BMI of 32.45 and a standard deviation of ~6.88. The BMI range varies from 18.2 to 67.1 with 1st, 2nd(median), and 3rd percentiles of 27.5, 32, and 36.6, respectively.

(4) Pairplot generates a matrix of axes representing the relationship for each column pair in a dataset. In the diagonal axes, it also creates the univariate distribution of each variable. Here, on the diagonal axes, we can observe the univariate distribution of each glucose, skin thickness, and Diabetes pedigree function based on 2 outcomes (0 represents non-diabetic and 1 represents diabetic). Moreover, six other plots are the bivariate distribution between glucose-skin thickness, glucose-diabetes pedigree function, and skin thickness-diabetes pedigree function, repeated twice based on two different toned outcomes (0 represents non-diabetic and 1 represents diabetic).

(5) Most of the insulin levels are around 100-200, and glucose levels range from 80-150. Also, this scatterplot does not observe a significant correlation between insulin and glucose.

(6) Based on the 1st histogram, most of the diabetic women groups in the 20-29years age group, and the least diabetic women age group is 60-69years. Based on the 2nd histogram, most of the non-diabetic women groups are in the 20-29 age group, and the least non-diabetic women age group is 70-79 years. For both cases, women aged 20-29 are prominent. Also, both histograms are right-skewed. However, non-diabetic data contains a heavy tail.

(7) From the heatmap, the color bar is helpful in determining the most correlated attributes easily. The lighter the color, the higher the correlation in this heatmap. Most cells have relatively low correlation values (except diagonal 1; those are autocorrelation values. So it will always be 1 for all cases). However, higher correlations are observed between pregnancies-age (r = 0.54) and BMI-sickness(r=0.53).
