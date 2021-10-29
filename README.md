# Customer-Segmentation
Determining customer segments with K-means Clustering using Python

# Business Problem : 
# How a shopping plaza marketing business can use effective promotion to segment their customer database to attract more customers and increase revenue?

Marketing teams in Shopping Centre investement are hugely driven in the race to increase their customer base. Effective promotion can garner customers' attention and loyalty. Data , such as types of customers, family size, income etc, are often collected but always not put into good use. No matter how terrific a sales promotion seems like, business need to break down their customer base down to a more narrow, specific group in order to achieve best ROI. This machine learning model will be able to solve this problem for the business by grouping customer with similar means and thus increasing the foot traffic.

## Introduction
Customer segmentation helps the marketing team to recognize and expose different customer  segments that act differently and thus follow different purchasing strategies. Customer segmentation helps in figuring out the customers who vary in terms of preferences and expectations.  The  main  purpose  of  performing customer segmentation is to group people, who have similar interest so that the marketing team can work together in an effective marketing  plan.

# Data Collection
The dataset is retrieved from Kaggle. It contains 200 customer records with 4 features like gender,age, income and a spending score of the cutomer. The spending score is given to the customer based on their spending pattern.The machine learning model should be able to predict future house price in this county

# Exploratory Data Analysis with Feature Engineering
Here in this notebook I do basic exploratory data analysis on the dataset to get an understanding of the data. Python packages like matplotlib and seaborn are used. Things I covered :

* Understanding the overall data
* Analysing each of the variables and their interaction by visualizing the trends
* Created few features with the help of existing features and visualize them

## Data Insights

**1. Gender Distribution -** - 56% percent of the database is female category. 

![image](https://user-images.githubusercontent.com/49127037/139367003-b1ee4102-b469-4806-9e0f-ed75fa1519d2.png)

**2.Distribution of age,spending-score and income -**  The features are more or less follow a normal distributed. Also we see here, majority of the spending score is between 40-60.

![image](https://user-images.githubusercontent.com/49127037/139367240-f5aac4c4-4104-404d-8042-7d27d49f65b0.png)

**3. Frequency of the age-range -**  We see that the majority of the customer base is from _**'Adult' group which are between 20-40 age-band**_

![image](https://user-images.githubusercontent.com/49127037/139370122-2a319600-edf6-432d-9cab-7f267d290bca.png)


**4. Relationship between the age and Spending score of the customers -** There is a negative relationship between Age and the Spending pattern . Higher is the age, lower is the spending score. It implies that with age, mostly the customer are turning into risk averse.

![image](https://user-images.githubusercontent.com/49127037/139368655-6a51a510-23f6-4284-a440-1b7e6d2f6bdf.png)

**5. Relationship of the numerical features(age,income,spending score) with Gender -**

- _**Prominent Age Range**_- The most prominent age range is between 30 and 40 for both male and female. Though, we have significant numbers from 20 through to 50.
- _**Majority of the database**_-  The two most frequent age bands are 20-30 and 30-40. Among them, _**female**_ are the majority
- _**Senior customers**_ -  Be it male or female, Seniors have no higher Spending Score than 60.

![image](https://user-images.githubusercontent.com/49127037/139366114-4bd5fd8b-08b0-461c-aee1-a6b061241de3.png)




