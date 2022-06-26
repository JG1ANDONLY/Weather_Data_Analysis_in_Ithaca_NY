# Weather Data Analysis in Ithaca, NY from 2021.01 to 2022.04
### Data Analysis & Model Building Report for the *INFO 1998 Introduction to Machine Learning* Final Project
Authors: <br>
Zhongyi (James) Guo (zg268@cornell.edu) <br>
Zixian (Maggie) Huang (zh359@cornell.edu) <br>
**Authors are in no particular order.** <br>
Github Repository: https://github.com/JG1ANDONLY/Weather_Data_Analysis_in_Ithaca_NY <br>
Date: 04/27/2022
<hr/>
In this report, we first raised a quesiton: Can the range of temperature support predictions of snowing? We performed data cleaning on the raw dataset for easier later reference and saved the cleaned dataset as `final_data.csv`. <br><br>

Then, we performed Exploratory Data Analysis (EDA) to detect patterns among some variables that we are interested in studying, and discovered potential relationships between the daily range of temperature (min temperature & max temperature) and the amount of snow. Next, we decided to build two models using Logistic Regression and K-Nearest Neighbors algorithm. <br><br>

We did train-test split and tested the accuracy scores of both models. We reached the model accuracy at **0.809** for the Logistic Regression model and at **0.786** for the K-Nearest Neighbors model with k = 10. Afterwards, confusion matrices were plotted for model tuning & validating and error analysis. <br><br>

Finally, we reached a conclusion that the daily temperature range can efficiently forecast snowing in Ithaca, NY.
