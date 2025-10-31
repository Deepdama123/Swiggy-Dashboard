# Swiggy Data Analysis Dashboard

This project is a comprehensive analysis of Swiggy restaurant data, visualized using Microsoft Power BI. The dashboard provides insights into restaurant distribution, pricing, ratings, and popular food types across various cities in India.

## 📊 Dashboard Preview

Here is a preview of the main dashboard page:
<img width="1290" height="705" alt="image" src="https://github.com/user-attachments/assets/04b3b855-b892-46c7-b25a-301fbfd95246" />

## 🚀 Key Features & Insights

This interactive dashboard allows users to explore Swiggy data dynamically.

### Key Performance Indicators (KPIs)
The main page highlights five key metrics for a high-level overview:
* **Total Restaurants:** 106.60K
* **Total Cities:** 97
* **Average Rating:** 3.8 / 5.0
* **Average Price:** ₹330.14
* **Average Delivery Time:** 42 Minutes

### Visualizations
* **Top 10 Cities by Restaurants:** A bar chart showing the cities with the highest concentration of restaurants (e.g., Bangalore, Mumbai, Chennai).
* **Top 10 Food Types:** A bar chart identifying the most commonly offered cuisines (e.g., North Indian, Chinese, South Indian).
* **Total Restaurants by City (Map):** A bubble map that provides a geospatial view of restaurant density across the covered cities.
* **Avg Rating vs. Avg Price by City:** A scatter plot that helps identify relationships and outliers. For example, which cities have high ratings but low prices, or vice versa.
* **Restaurant Details:** A detailed table view that allows for drilling down into specific restaurant data.

### Interactive Filters
The report is fully interactive and can be filtered by:
* City
* Area
* Food Type
* Price Range

---

## 💿 Data Source

The analysis is based on a single dataset, `swiggy.csv`, which contains restaurant listings.

**Dataset Schema:**
* `ID`: Unique identifier for the restaurant.
* `Area`: The neighborhood or locality.
* `City`: The city where the restaurant is located.
* `Restaurant`: The name of the restaurant.
* `Price`: The approximate price for a meal.
* `Avg ratings`: The average user rating.
* `Total ratings`: The total number of ratings received.
* `Food type`: The cuisines offered (e.g., "Biryani, Chinese, North Indian").
* `Address`: The specific address of the restaurant.
* `Delivery time`: The estimated delivery time in minutes.

---

## 🛠️ Tools Used

* **Microsoft Power BI:** Used for data modeling, creating DAX measures, and building all visualizations.

---
