![alt text](https://imgcdnblog.carmudi.com.ph/wp-content/uploads/2020/07/01084228/Waze-Logo.png)

# Project Overview and Purpose
This is a project from Google Advanced Data Analytics.

We aim to conduct a data analytics project for the Waze app. Waze is a free navigation app similar to google maps that helps drivers around the world to get to where they want to go. The final goal is to develope a classification model to predict churn. 
Developing a churn prediction model will help prevent churn, improve user retention, and grow Waze’s business. An accurate model can also help identify specific factors that contribute to churn and answer questions such as:

Who are the users most likely to churn?
Why do users churn?
When do users churn?


First, we need to conduct data preparation and get insight from the available dataset. Data visualization and Hypothesis testing may provide us with useful information. Then, several models including linear regression, random forest, and XGBoost are built to predict churn.

The dataset columns are:

**ID**:	A sequential numbered index

**label	obj**: Target variable (“retained” vs “churned”) for if a user has churned anytime during the course of the month

**sessions**: The number of occurrences of a user opening the app during the month

**drives**:	An occurrence of driving at least 1 km during the month

**device**:	The type of device a user starts a session with

**total_sessions**:	A model estimate of the total number of sessions since a user has onboarded

**n_days_after_onboarding**: The number of days since a user signed up for the app

**total_navigations_fav1**:	Total navigations since onboarding to the user’s favorite place 1

**total_navigations_fav2**:	Total navigations since onboarding to the user’s favorite place 2

**driven_km_drives**:	Total kilometers driven during the month

**duration_minutes_drives**:	Total duration driven in minutes during the month

**activity_days**:	Number of days the user opens the app during the month

**driving_days**:	Number of days the user drives (at least 1 km) during the month

## We aim to:

1. **Get information from the raw data**
   
   1.1 Compare churned users using different devices (IOS, ANDROID)
   1.2 Visualize data to understand the feature distributions and clean the data
  

2. **Conduct a t-test** to check whether or not there is a difference in average number of drives between drivers who use iPhone devices and drivers who use Androids.

3. **Build linear regression models** to predict user churn based on a variety of variables

4. **Build machine learning models** (Random Forest, XGBoost)  to predict user churn. Our model will help leadership make informed business decisions to prevent user churn, improve user retention, and grow Waze’s business.
