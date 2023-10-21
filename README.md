# data-analysis-data-visualization
## statistics for data scientist
Data science includes extracting data and results, and statistics focus on the analysis and communication of the data results. Statistical data science works to explain the trends and results of a data set by identifying the statistical correlations and distribution of variables and values.

### probability
The probability is the measure of the likelihood of an event to happen. It measures the certainty of the event. The formula for probability is given by; P(E) = Number of Favourable Outcomes/Number of total outcomes.

example of probability :

First we need to have a number of favourable outcomes or as known as n(A). Here we will calculate what percentage chance a male passenger has of surviving from all the ship's passengers

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/19b4a0f3-c1a3-4f65-8795-82a091a0520d)

after that wee need  total number of events in the sample space or n(S).

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/4dd6744e-20e3-4d2d-aa49-1b9cee9cb1ae)

then, We have to enter the values we got earlier into the probability formula = P(A) = n(A)/n(S)

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/c0beeeaa-f60c-46b7-a1b5-9c47822fe69a)

### Measure of central tendency
The central tendency measure is defined as the number used to represent the center or middle of a set of data values. The three commonly used measures of central tendency are the mean, median, and mode.

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/b188a2ec-fbaa-494e-802e-3140536e37ab)

### Range
Range, which is the difference between the largest and smallest value in the data set, describes how well the central tendency represents the data.

example of range :

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/9dc1fc83-6b88-413b-a1a2-ad89f9d320eb)

### Variance
The term variance refers to a statistical measurement of the spread between numbers in a data set. More specifically, variance measures how far each number in the set is from the mean (average), and thus from every other number in the set.

example of variance :

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/84561d59-ab93-4bd9-a9bd-58649dcf8c9e)

### Standard Deviation
A standard deviation is a measure of how dispersed the data is in relation to the mean. Low, or small, standard deviation indicates data are clustered tightly around the mean, and high, or large, standard deviation indicates data are more spread out.

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/e45a07ec-70a6-48e5-bfd3-88f9a39e75c2)

### Quantile
Quantiles are values that split sorted data or a probability distribution into equal parts.

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/5bb6ab2e-5a9c-494e-a5bd-8e68b0335878)

## Hypothesis Testing
Hypothesis testing is a systematic procedure for deciding whether the results of a research study support a particular theory which applies to a population. Hypothesis testing uses sample data to evaluate a hypothesis about a population.

libraries that are needed in hypothesis testing

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/d770f407-2f3d-4a76-a61c-15074e767aaf)

in hypothesis testing there are t-test and p values. A t test is a statistical test that is used to compare the means of two groups. The P value is defined as the probability under the assumption of no effect or no difference (null hypothesis), of obtaining a result equal to or more extreme than what was actually observed.

example of hypothesis testing :

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/86047e67-7377-4266-b2be-8a4f17064000)

## Simple Linear Regression
Simple linear regression is a regression model that estimates the relationship between one independent variable and one dependent variable using a straight line. Both variables should be quantitative.

For example, here we’re gonna do a simple linear regression using height-weight dataset :

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/707305ab-a593-4680-85a6-92dbf9f01b90)

here we create two variables x and y, then we have to separate the train set and test set using train size 1/3 and random state 42.

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/346b75c5-d9ff-4f7c-9bd8-c45de95a62ce)

here we store the LinearRegression into variable named regressor and fitting it into training. We also can see the coefficients.

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/ab23756f-cea0-4550-8a0f-559a6061d6a7)

After that, we’re going to predict the result, y_pred is a variable that will store the output and X_test is the predictor. And then we create a variable called result which contains the actual values and the predict values.

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/0b036410-fd61-4c2e-a267-e54986310c78)

scatter plot output :

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/5cb7a43e-ea75-4e7b-8367-89ccee587eee)

Here we can see the MSE, MAE, MAPE, and r2 values. The r2 value is 0.98 or 98%, if the r2 value is closer to 1 or 100%, the more accurate the forecasting results are

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/fca3a635-0a5f-418d-b03e-3ebde0078fa5)

# data visualization
The process of finding trends and correlations in our data by representing it pictorially is called Data Visualization. To perform data visualization in python, we can use various python data visualization modules such as Matplotlib, Seaborn, Plotly, etc. here we're going to use matplotlib and seaborn. Matplotlib is a cross-platform, data visualization and graphical plotting library (histograms, scatter plots, bar charts, etc) for Python and its numerical extension NumPy. Matplotlib is powerful tool for executing a variety of tasks. It is able to create different types of visualization reports like line plots, scatter plots, histograms, bar charts, pie charts, box plots, and many more different plots. Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

- Line chart
  A line chart is a type of chart used to show information that changes over time. Line charts are created by plotting a series of several points and connecting them with a straight line. Here is an example how to create a line chart using matplotlib with darkgrid seaborn style.

  ![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/42acc2e1-6af9-49ce-9237-90a9b43bfb10)

output :

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/c057e038-6c32-4b39-9498-71fd01cbe06b)

- Bar graph using matplotlib
  A bar graph is a graphical representation of information. It uses bars that extend to different heights to depict value. Here is how to make a bar graph using matplotlib :
  
  ![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/827b4fb9-3db0-433d-a82c-da5d5393ce96)

output :

![image](https://github.com/fadillahrahmadaniyah/data-analysis-data-visualization/assets/147982664/b320f5e4-187a-48a9-b7f2-a00c80df331f)
