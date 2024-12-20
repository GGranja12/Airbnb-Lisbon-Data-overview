# Airbnb - Lisbon at a Glance ✈️🅰️

![image](https://github.com/user-attachments/assets/5548fa82-4ff9-4b7a-a9d0-402844a64f89)


## *Project Overview* 📝

#### Welcome to my Airbnb Lisbon's Listings Exploratory Data Analysis!

This mid-project was developed during Ironhack's Data Analytics course, aiming to showcase and solidify the knowledge acquired over the past months. The project focuses on applying visualization and Python skills, exploratory data analysis techniques, and the development of machine learning models. 

## *The Dataset* 🗃

The data was retrieved from 2 different csv. files (lisbon_weekdays.csv and lisbon_weekends.csv) which can be downloaded by accessing this [Kaggle page](https://www.kaggle.com/datasets/thedevastator/airbnb-price-determinants-in-europe?select=lisbon_weekdays.csv) The Airbnb listings were originally webscrapped by Kristóf Gyódi and Łukasz Nawaro to develop their paper ["_Determinants of Airbnb prices in European cities: A spatial econometrics approach_"](https://www.sciencedirect.com/science/article/pii/S0261517721000388?via%3Dihub).

The provided csv. files comprise 2019 data of Airbnb listings available in Lisbon, either respective to weekday bookings (Tuesday-Thursday; lisbon_weekdays.csv) or to weekend bookings (Friday-Sunday; lisbon_weekdends.csv). Both files present one listing price column and 18 attributes as follows:

- **realSum**: the full price of accommodation for two people and two nights in EUR
- **room_type**: the type of the accommodation
- **room_shared**: dummy variable for shared rooms 
- **room_private**: dummy variable for private rooms
- **person_capacity**: maximum number of guests
- **host_is_superhost**: dummy variable for superhost status
- **multi**: dummy for listings offered by hosts with 2–4 listings
- **biz**: dummy for listings offered by hosts with more than 4 listings
- **cleanliness_rating**: cleanliness rating
- **guest_satisfaction_overall**: overall rating of the listing (scale to 100)
- **bedrooms**: number of bedrooms (0 for studios)
- **dist**: distance to the city centre in km
- **metro_dist**: distance from nearest metro station in km
- **attr_index**: attraction index of the listing location
- **attr_index_norm**: normalised attraction index (0-100)
- **rest_index**: restaurant index of the listing location
- **rest_index_norm**: normalised restaurant index (0-100)
- **lng**: longitude of the listing location
- **lat**: latitude of the listing location

## *Project Development* 

This [Trello board](https://trello.com/b/DUtscQkn/ironhack-midproject) provides access to the project's workflow, detailing all tasks developed over the three-week period.

#### *Data Visualizations* 📊

After applying data preparation and cleaning techniques in a Python notebook I developed Tableau dashboards to provide the audience with a clear and straighforward overview of insightful aspects related to our target feature: real estate prices in King's County. 

No spoiler needed - just take a look and [explore it for yourself](https://public.tableau.com/views/Book1_17325726562400/PriceForecasters?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

#### *Supervised Machine Learning - Regression Models* 🦾 📈

Keeping in mind that our target feature is price, the machine learning process was divided into four distinct perspectives:

**1.** Applying six different supervised models (Linear, Lasso, Ridge, Decision Tree, KNN, XGboost) while keeping all the 20 dataset features;

**2.** Applying the same six supervised models (Linear, Lasso, Ridge, Decision Tree, KNN, XGboost) while dropping dataset features based only on histogram insights;

**3.** Applying the Linear Regression supervised model while dropping dataset features after addressing multicollinearity and outliers;

**4.** Fine-tuning the XGboost supervised model applied to all dataset features using the GridSearch hyperparameter tuning. 

As a final step, we calculated and compiled four different metrics (R2, RMSE, MSE and MAE) for each one of the fourteen models, to facilitate the comparison of their fitness and predictive capacity. 

#### *Presentation* 🎬

For a summarized overview of the project feel free to access the [Canva presentation](https://www.canva.com/design/DAGXtYJOijc/vAH_wwsND7MN5hUE9gookQ/edit?utm_content=DAGXtYJOijc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).
## *Final Remarks* ✏

Special thanks to my teachers, Isidre and Nicolas, for all the support and feedback.
