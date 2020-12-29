# Data Analysis Projects

Two Projects: Regression Analysis of House Sales in King County and Statistical Inference of Salary Increase By Major. 

## Project 1:  Regression Analysis of House Sales in King County

### Introduction

The majority of people at one point in their life face the realities of real estate. Thus, I have decided to prepare myself for the future by looking into possible factors contributing to house prices. In this report, we explore the dataset about the selling price of houses in King 3 County from May 2014 to May 2015, published Kaggle.com . For the main part of this analysis, we construct a multiple regression model by the forward selection, using adjusted R-squared and R-squared since they are a better indicator of the degree to which the model explains the data, the fitness of the model than p-value. Also, we construct a p-value test to test the statistical significance of the model. Therefore, the question we are discovering is, “Based on the gathered data of the house sales in King County from May 2014 to May 2015, which factors affected the selling price of the house the most?”. Analyzing this question gives us valuable information about which properties of the house are better investments in case we decide to sell our house.

### Dataset

The data is gathered from year-long research involving 21,613 houses in King County, Washington. It comprises the sold price of the house, 19 house features, such as number of bedrooms, the size of the living room, and ID number for the sold house. Those columns serve as our alleged independent and dependent variables, respectively. The “price” column, continuous polytomous quantitative variable as we can see from the basic dataset information, is the responding variable with the unit of USD. The rest are predictor variables. However, instead of using all of them for our model, we are building a correlation matrix to check which of those variables have the highest correlation to the responding variable. Before creating a matrix, we look if there are any non-numerical values and convert them into numerical. Then, we clear out the dataset and start to process it.

### [Link to full paper](https://github.com/hamidliii/Data-Analysis-and-Processing/blob/main/MULTIPLE%20REGRESSION%20AND%20CORRELATION%20FOR%20HOUSING%20PRICE.pdf)
### [Link to code base](https://github.com/hamidliii/Data-Analysis-and-Processing/blob/main/Regression%20Analysis%20of%20House%20Sales%20in%20King%20County.ipynb)


## Project 2: Statistical Inference of Salary Increase By Major

### Introduction

Choosing a major in college is always a hard decision for the students. Based on the dataset given about Undergraduate Majors and their corresponding salaries, we will look into which set of majors is more profitable to go into. The original dataset about salaries and majors gives us information about median salaries right after graduation and in the mid-career of the graduates. To find out if getting a degree in Computational Sciences (CS) majors will be more or less profitable than getting a Social Sciences (SS) degree, we use statistical and practical significance tests. So, the question we will be discovering is “Based on the gathered data of current graduates, are the CS majors earning more than the SS graduates?”. Analyzing this question will give us valuable information about which majors are better investments.

### Dataset

The dataset used in the analysis is from The Wall Street Journal (2017) dataset of "Salary Increase By Major". The data is gathered from a year-long research involving 1.2 million people from over 300 US colleges with only a bachelor's degree by PayScale Inc. about their salaries. The dataset includes information about the change in the salary from the start to mid-career, percentiles of the mid-career salaries from 10th to 90th and median start and mid-career salaries. From this dataset, we will be working with two columns of the table comparing the salaries by majors, Undergraduate Major name and Mid-Career Median Salary, as we will be using the hypothesis testing for the difference of the mean. Those two columns will serve as our alleged independent and dependent variables, respectively. The former, being qualitative and categorical, will help us divide the dataset into different categories such as CS majors and SS majors, and the latter, which is a quantitative and continuous variable, but treated as discrete because it is rounded in dataset, showing median salaries, will help us make numerical conclusions about the data, such as graduates with X degree earn XXX more on average than graduates with Y degree. The confounding variable could be the school from where the degree is obtained since this also contributes to the final results after graduation. Thus, serving as another independent variable the name of the school can have an effect on the salaries of the graduates. While we don’t really measure if the worker has gotten a master’s degree or not, the degree after undergraduate can still play a role in determining the salaries of workers. The master’s degree ownership can serve as the extraneous variable in this scenario.

For the analysis, I have sorted out data into two categories: CS majors and SS majors median mid-career salaries. As I am aiming to help Minerva students in their decision about which major to declare next year, the categories include majors which are similar to the ones offered at Minerva.

### [Link to full paper](https://github.com/hamidliii/Data-Analysis-and-Processing/blob/main/Statistical%20Inference%20of%20Salary%20Increase%20By%20Major.pdf)
### [Link to code base](https://github.com/hamidliii/data-analysis-CS50/blob/main/Statistical%20Inference%20of%20Salary%20Increase%20By%20Major.ipynb)


