# Automobile Modeling
This project centers around the intricate task of 
automobile modeling, where an in-depth analysis is conducted on diverse 
variables within a structured dataframe. The primary objective is to 
unravel the intricate relationships and dependencies that exist between 
these variables: 
'highway-mpg', 'body-style', 'make' (the different brands of vehicles), 'engine-size', 'engine-type' and compared them to the pricing of vehicles. 

By leveraging data exploration and visualization techniques, this project aims to provide valuable insights into the factors influencing the pricing dynamics of automobiles.

## Introduction
We utilized an automobile dataset from from the University of California Irvine Machine Learning (UCIML) Repository. The dataset was derived from the 1985 Ward's Automotive Yearbook. In order to access our data frame which was in a .data file, we imported a fetch command (fetch_ucirepo) from the UCIML repository and assigned the data frame to the automobile variable. After performing exploratory data analysis and preprocessing, we narrowed down our target variable of price. We were especially interested in how potential predictor variables such as make, body style, horsepower, and engine size could predict for price.

For more information, view here:
(https://archive.ics.uci.edu/dataset/10/automobile)

### Methods Used
Throughout the course of this project, a variety of methodologies were employed to achieve our objectives. Notably, a Linear Regression Model was employed to predict the pricing dynamics. This model proved instrumental in forecasting continuous pricing patterns and discerning key features within the spectrum of automobile models. While the application of Linear Regression facilitated intuitive visualization, a nuanced understanding of all features necessitated additional cognitive effort. Furthermore, the utilization of Pandas played a pivotal role in the graphical representation of our data. The integration of Pandas enhanced our ability to present comprehensive insights through visually compelling graphs, thereby augmenting the communicative efficacy of our findings.

### Technologies
- Jupyter
- Python
- Pandas
- Seaborn
- Matplotlib
- Numpy
- Ucimlrepo
- Sklearn linear model, pre processing, model selections, metrics
- Warnings
- OS

### Impact
The linear regression indicates that prices are highly reflected in the components of cars. When consumers decide to purchase a car, depending on the features of the automobile, it will have a high impact on prices. Each feature either can increase or decrease the prices.

**This heatmap shows the correlation matrix between all of the numerical values**
<br><br>
![image 1](https://github.com/elliotbabilonia/automobile-project/assets/111297159/9c64b3c9-23c5-4217-a158-d62d7178c04b)
<br><br>
**This bar plot shows the top 10 features and their corresponding coefficients**
<br><br>
![image 2](https://github.com/elliotbabilonia/automobile-project/assets/111297159/042a1481-f9bd-4e20-9196-c960f54030a2)

## Summary

Some of the challenges we faced with the automobile dataframe was retrieving the corrrect library to download the dataframe, and deciding which type of graphs would be best to use in the Exploratory Data Analysis (EDA). Creating the linear progression model was the most challenging because of the mathematical parts that was needed to build the model.

### Credit
- Alex Nepomuceno (Severesix907)
- Amarylis Valentin (walcotttt)
- Elliot Babilonia (elliotbabilonia)
- Jianhang Xiao (Jianhang-Xiao)
- Patricia Cordero (chica25)
