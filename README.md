# 📊 New York Airbnb 2024 - Exploratory Data Analysis (EDA) using Python  
![image](https://github.com/krishnakumarpv1010/Airbnb-NYC-EDA-2024/blob/main/download.jpeg?raw=true)

## 📌 Project Overview  
This project focuses on **Exploratory Data Analysis (EDA)** of the **New York Airbnb Open Data 2024** using Python.  
We analyze **pricing trends, availability, host distribution, ratings, and licensing status** across different boroughs in NYC.  
By leveraging **data visualization and statistical analysis**, we uncover key insights into the Airbnb market dynamics.  

---

## 📂 Dataset Information  
- **Dataset Name**: New York Airbnb Open Data 2024  
- **Source**:  Kaggle  
- **Size**: 20758 x 19
- **Key Features**:  
  - `price` – Cost per night of the listing  
  - `room_type` – Type of accommodation (Entire home, Private room, etc.)  
  - `availability_365` – Number of days the listing is available per year  
  - `number_of_reviews` – Count of reviews for each listing  
  - `rating` – Customer rating of the listing  
  - `neighbourhood` – Name of the locality  
  - `borough` – NYC borough (Manhattan, Brooklyn, etc.)  
  - `license` – Whether the listing is licensed or not  

---

## 🔍 Key Analysis & Insights  
✔️ **Pricing Trends** – How prices vary across different boroughs and room types.  
✔️ **Host & Property Distribution** – Identifying the concentration of Airbnb hosts in different neighborhoods.  
✔️ **Ratings & Reviews** – Exploring the relationship between price and customer reviews.  
✔️ **Availability Trends** – Evaluating listing availability (Availability_365) patterns.  
✔️ **Licensed vs. Non-Licensed** – Understanding the distribution of licensed vs. non-licensed properties.  

---

## 📊 Data Visualization & Plots  
We use **Matplotlib & Seaborn** to create various visualizations:  
- **Bar Charts** – Comparing prices across boroughs and room types.  
- **Boxplots** – Identifying outliers in pricing.  
- **Heatmaps** – Showing correlations between numerical variables.  
- **Histograms** – Displaying the distribution of prices.  
- **Scatter Plots** – Analyzing the relationship between price and availability.
- **Pairlot** - show the relationship between numeric values
- 

## 🛠 Technologies Used
Programming language - Python
- **Data cleaning** - Numpy & Pandas
- **Data visaulization** - Matplotlib & Seaborn

## Key steps in the project
- **1️⃣ - Data Preprocessing & Cleaning**
-imported the New York Airbnb Open Data 2024 and handled missing values, data types, and outliers (filtered price < $1500).

- **2️⃣ Exploratory Data Analysis (EDA) & Visualizations**
-Used pandas, matplotlib, and seaborn to analyze price trends, room types, borough-wise distributions, and correlations through bar plots, boxplots, histograms, 
 and heatmaps.


 - **3️⃣ Insights & Conclusion**
 -Found that lower-priced properties get more reviews, Manhattan has the highest prices, and identified boroughs with the most unlicensed listings.


## 📜 Key Findings and Insights

1) Price Distribution Insights:

   * The majority of Airbnb listings are priced within an affordable range, but there are some high-price outliers,       especially in Manhattan.
   
   * Entire homes/apartments cost significantly more than private or shared rooms.

2) Neighbourhood Group Trends:

   * Brooklyn and Manhattan have the highest number of listings, making them key areas for Airbnb activity.

3) Host Activity & Market Trends:

   * A significant number of hosts have multiple listings, indicating professional hosting in some areas.

   * Understanding licensed vs. non-licensed listings helps identify legal and compliance issues.

4) Guest Experience & Ratings:

   * Higher-rated properties tend to have reasonable pricing and better amenities.   
   * The analysis reveals an inverse relationship between price and the number of reviews, indicating that lower-priced properties tend to receive more reviews. This suggests that budget-friendly listings attract a higher number of guests, leading to more frequent feedback and engagement.


5) Enhancing Availability & Occupancy

   * Some boroughs have low availability (availability_365 < 100 days/year), limiting booking opportunities.
   * Increasing availability and optimizing minimum night stays can attract more guests.

5) Latitude & Longitude Correlation:

   * Most of the entire home/apt are situated in (-40.75,-74.05)

6) Future Data-Driven Decisions:

   * Implementing machine learning models could improve price prediction and occupancy rates.



















