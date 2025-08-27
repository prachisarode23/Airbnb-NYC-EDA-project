# 🏠 NYC Airbnb Data Analysis (2019)

## 📌 Project Overview
This project explores the **New York City Airbnb dataset (2019)** to uncover insights about rental prices, neighborhood trends, and property types.  
The goal is to demonstrate **data cleaning, exploratory data analysis (EDA), and visualization skills** using Python.

---

## 📊 Dataset
- **Source:** [Airbnb NYC Open Data (Kaggle)](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)  
- **Rows:** ~49,000  
- **Columns:** 16 (neighbourhood, borough, room type, price, etc.)

Key fields:
- `neighbourhood_group` → Borough (Manhattan, Brooklyn, etc.)  
- `room_type` → Entire home/apt, Private room, Shared room  
- `price` → Price per night (USD)  
- `minimum_nights`, `reviews_per_month`, `availability_365`, etc.

---

## ⚙️ Tools Used
- Python 3.9  
- Pandas – data wrangling  
- Matplotlib & Seaborn – visualizations  
- Jupyter Notebook  

---

## 🔎 Analysis Steps
1. **Data Cleaning**
   - Removed missing values in key fields.
   - Filtered unrealistic listings (prices > $1000).
   - Prepared dataset for analysis.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of room types.
   - Price variation across boroughs.
   - Top neighborhoods by price.
   - Listings distribution per borough.
   - Correlation analysis of numerical features.

3. **Visualization**
   - Bar plots, histograms, heatmaps for storytelling.

---

## 📈 Key Visualizations
- 📊 Room Type Distribution  
- 🗽 Average Price by Borough  
- 💰 Price Distribution (Histogram)  
- 🏙️ Top 10 Neighborhoods by Avg. Price  
- 📌 Number of Listings per Borough  
- 🔥 Correlation Heatmap  

---

## 💡 Insights
- **Manhattan** has the highest average Airbnb prices; **Bronx/Queens** are more affordable.  
- **Entire homes/apartments** are most expensive; **shared rooms** are cheapest.  
- Most listings are priced **under $300/night**.  
- Luxury neighborhoods like **Tribeca & Soho** dominate the top-priced listings.  
- Long-term availability and high price do not strongly correlate with reviews.  
