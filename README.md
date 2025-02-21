# 📊 New York Airbnb 2024 - Exploratory Data Analysis (EDA) using Python  
![image](https://github.com/krishnakumarpv1010/Airbnb-NYC-EDA-2024/blob/main/download.jpeg?raw=true)

## 📌 Project Overview  
This project focuses on **Exploratory Data Analysis (EDA)** of the **New York Airbnb Open Data 2024** using Python.  
We analyze **pricing trends, availability, host distribution, ratings, and licensing status** across different boroughs in NYC.  
By leveraging **data visualization and statistical analysis**, we uncover key insights into the Airbnb market dynamics.  

---

## 📂 Dataset Information  
- **Dataset Name**: New York Airbnb Open Data 2024  
- **Source**: _(Specify dataset source, e.g., Inside Airbnb or Kaggle)_  
- **Size**: _(Total number of rows & columns after loading the data)_  
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

**Example Visualization:**
```python
plt.figure(figsize=(10,6))
sns.boxplot(x='borough', y='price', data=df)
plt.title('Price Distribution Across Boroughs')
plt.show()
