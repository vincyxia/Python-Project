# MSBA Python Final Project - NYC Airbnb Listing Analysis

## Project requirement

**Goal** : Detect **three** interesting, nontrivial, and somewhat unexpected finding in a real-world data set of your choice.

**Format** : 

* Data set description
* One section on data clean-up/preparation
* Findings, including a brief summary, a set of tables and charts and managerial insights.

## Project description

NYC Airbnb listing data is from Kaggle.
The three interesting findings are as below:

**1. Price analysis.**

> We want to know how different attributes that can affect the price of Airbnb's listings. 
> 
> At the beginning, we explored "room types", " seasonality", and " boroughs" within our dataset. Unfortunately, we didn't find any unexpected facts about the price. So, we decided to look at some other attributes that outside our data. 
> 
> We combined criminal cases, interest spots, and museum areas with our data. 
> 
> Eventually, we did find something that interests us, pls refer to jupyter notebook for detail.

**2. Listing name analysis.**

> We are very interested in the relationship between listing names and the popularity of Airbnb listings. 
> 
> So, we performed a sentiment analysis using the logistic regression model to find which words have the most impact on popularity. 
> 
> Beyond that, we also conducted a comparative analysis, comparing new york city's listing names with san Francisco’s listing names to find their similarities and differences.

**3. Clustering analysis**

> In the third part, we switched our perspective from guests to hosts. 
> 
> As we were working on the project, we found that there was more than one type of host. 
> 
> So, we utilized KMeans to see if there are different types of host, and if so, what are the features of each type of host.
