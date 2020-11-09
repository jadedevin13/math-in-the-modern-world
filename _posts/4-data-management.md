---
title: '4 Data Management'
excerpt:
  »	use a variety of statistical tools to process and manage numerical data (S) <br/>
  »	use methods of linear regression and correlations to predict the value of a variable given certain conditions (S) <br/>
  »	advocate the use of statistical data in making important decisions (V) <br/>
order: 4
coverImage: '/assets/blog/4/Statistics.png'
ogImage:
  url: '/assets/blog/4/Statistics.png'
---

## What is Data Management

Data Management is application of methods for organizing and analyzing large amounts of information; solve problems involving probability and statistics; and carry out a culminating investigation that integrates statistical concepts and skills.

### Frequency Distribution

It is a group of data into categories showing the number of observations in each of the non-overlapping classes

*Class interval* - set of numbers defined by the lower and upper limits of a class relative to the class size

*Class boundary* - composed of the lower class boundary and upper class boundary. It is a number halfway between the upper class limit of one class the the lower limit of the next class interval.

*Class mark* - middle value of each class interval


#### Steps in creating a frequency distribution  in excel:
1. Put the data in column.
2. Create a table with the columns- class limits, class boundaries, lower limit, upper limit, frequency and class mark.  
3. Group the data according to given. 
4. To calculate the frequency, highlight the frequency column, type “ =frequency(data array,bins array) ” and press CTRL SHIFT ENTER.



### Frequency Distribution

![Frequency Distribution](/assets/blog/4/Freq-Dist.png)

Frequency polygon is a line graph where the frequency of each class interval is plotted against the corresponding class mark. The horizontal axis contains the class marks, while the vertical axis represents the frequency. 


### Histogram

![Histogram](/assets/blog/4/Histogram.png)

Histogram is a graph where rectangular bars are used to present the frequency distribution. The horizontal axis contains the class boundaries, while the vertical axis the frequencies. 


## Correlation and Regression

Correlation refers to relationship between two variables.

*Scatter plot/scatter diagram* - the graphical representation of bivariate data 




### Pearson's Product - Moment Correlation Coefficient

![Pearson Table](/assets/blog/4/Pearson-Table.png)

Pearson’s product-moment correlation coefficient is used to measure the linear relationship between two variables that are normally distributed. It is denoted by r. 

#### Steps in computing correlation in excel

1. Put and label data in each column.
2. In the dialog box, type “=correl”
3. Select all the data in the first column then type a “ , ”
4. Select all the data in the second column then enter


### Regression
- Regression analysis is a simple statistical tool used to model the dependence of a variable on one (or more) explanatory variables.
- Least square regression equation is an equation that is used to predict the value of the dependent variable based on the value of the independent variable.
- Least square regression line is the graphical representation of the least square regression equation and can be used to determine the approximate value of the dependent variable based on the value of the independent variable given in the scatter plot. 
- Coefficient of determination (r^2) is used to determine how well the least square regression line fits the sample data

#### Steps in creating regression equation in excel

1. Insert a scatterplot graph into a blank sheet.
2. Select the x-axis and y-axis data.
3. Right-click on any of the dots and select “Add Trendline” from the menu.
4. Select Display Equation on chart and Display R-squared value on chart on the chart boxes
