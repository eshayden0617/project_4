# Title: Predictive Forecasting: Is it wimdy?

-[Collaboration](#Collaboration)<br>
-[Project_Overview](#Overview)<br>
-[Methods](#Methods)<br>
-[Features](#Features)<br>
-[Target](#Target)<br>
-[Expected_Outcomes](#Expected_Outcomes)<br>
-[Outcomes](#Outcomes)


# Collaboration: 
<ul>
    <li>Eleanor Hayden</li>
    <li>Stefan Shover</li> 
    <li>Erika Walker</li>
</ul>

# Project_overview:
In a world where accurate weather predictions can significantly impact various sectors, our collaborative team—comprising Eleanor Hayden, Stefan Shover, and Erika Walker—embarks on a journey of Predictive Forecasting: Is it Wimdy?  We plan on taking historical weather data from Iowa State University (https://mesonet.agron.iastate.edu/request/download.phtml)  and train a neural network model.  Given current weather forecasts in Saint Louis (https://www.weather.gov/)  we are going to attempt to see how well our model can predict whether it will rain or not. Beyond a mere meteorological curiosity, our pursuit holds practical implications for industries like construction, sports events, and the everyday decisions of individuals planning activities such as picnics.

# Methods:
<ol>

<li>Data Collection: Training data will come from Iowa State University (https://mesonet.agron.iastate.edu/request/download.phtml).  While Testing data will come from Weather.gov (https://www.weather.gov/) for Saint Louis.</li>

<li>Data Cleaning: Utilizing Pandas, we will make sure that all data is comparable to each other (ie: features matching features between training sets and testing sets).  We will also make sure that data undergoes tensorization (vectorize the data so the machine learning algorithm can better interpret the features).</li>

<li>Crafting a model: We will first try gradient boosted models such as XGboost, we also built a Neural Network model that will hopfully be able to find patterns and predict wind speed.</li>
<ol>

# Features:
<ul>
    <li>Relative Humidity</li>
    <li>Temperature</li>
    <li>Dewpoint</li>
    <li>Wind Speed</li>
    <li>Short Forecast</li>
    <li>Is Daytime</li>
    <li>Mapped Forecast</li>

# Target:
<ul>
    <li>Wind Speed (Knots): Float value</li>
</ul>

# Expected_Outcomes:
This will be an interesting project to see if a machine learning model can be trained on historical data.  Then make rain predictions based upon current weather data.  We are designing this model to see how well it can predict rain or not.  We hope that our model will be >80% accuracy, given the features we have selected.

# Outcomes:
Seems that both methods XGBoosted Regression and Deep Neural network were unable to find patterns in our data.  We have come to the conclusion that we need more expanded features, or more data that is pertains to whether it would rain or not.  We had to make concessions with our data both historical and forecast.