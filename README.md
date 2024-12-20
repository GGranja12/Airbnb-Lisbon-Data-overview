# Airbnb - Lisbon at a Glance ✈️🅰️

![image](https://github.com/user-attachments/assets/5548fa82-4ff9-4b7a-a9d0-402844a64f89)


## *Project Overview* 📝

#### Welcome to my Airbnb Lisbon's Listings Exploratory Data Analysis!

This mid-project was developed during Ironhack's Data Analytics course, aiming to showcase and solidify the knowledge acquired over the past months. The project focuses on applying visualization and Python skills, exploratory data analysis techniques, and the development of machine learning models. 

## *The Dataset* 🗃

The data 

The csv. file can be downloaded by accessing this [Kaggle page](https://www.kaggle.com/datasets/minasameh55/king-country-houses-aa).

The provided dataset comprises one-year data (from May 2014 to May 2015) of house sale prices across King County, including Seattle, in the Washington State. It features 21 different columns, providing a comprehensive overview of the real estate market:

- **id**: A unique identifier for a house.
- **date**: The date on which the house was sold.
- **price**: The sale price of the house (**prediction target**).
- **bedrooms**: Number of bedrooms in the house.
- **bathrooms**: Number of bathrooms in the house, per bedroom.
- **sqft_living**: Square footage of the interior living space.
- **sqft_lot**: Square footage of the land space.
- **floors**: Number of floors (levels) in the house.
- **waterfront**: Whether the house has a waterfront view.
- **view**: Number of times the house has been viewed.
- **condition**: The overall condition of the house.
- **grade**: The overall grade given to the house, based on the King County grading system.
- **sqft_above**: Square footage of the house apart from the basement.
- **sqft_basement**: Square footage of the basement.
- **yr_built**: The year the house was built.
- **yr_renovated**: The year the house was renovated.
- **zipcode**: ZIP code area.
- **lat**: Latitude coordinate.
- **long**: Longitude coordinate.
- **sqft_living15**: The interior living space for the nearest 15 neighbors in 2015.
- **sqft_lot15**: The land spaces for the nearest 15 neighbors in 2015.

## *Quest Development* ⚙

The flowchart below presents our project methodology, acting as a guide to structure and properly develop the objective proposed:

![image](https://github.com/user-attachments/assets/5bc46c86-4d3e-4633-9e11-a0d20d47ed71)

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
