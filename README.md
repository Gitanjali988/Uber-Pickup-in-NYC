# 🚖 Uber Pickup Analysis in NYC

This project analyzes Uber pickup data in New York City using clustering and visualization techniques to uncover patterns in rider behavior across boroughs and Bronx.

## 📊 Overview

- 🔍 Dataset includes Uber pickups from April to September 2014 and January to June 2015
- 🗺️ Explores geographic pickup patterns using clustering (KMeans, DBSCAN, OPTICS, BIRCH)
- 📈 Visualizes temporal trends (hourly, daily, and by borough) using heatmaps and charts
- 🧠 Provides actionable insights into peak demand and strategic pickup zones

---

## 🛠️ Tools & Technologies

- **Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Libraries:** Scikit-learn, Folium, Plotly
- **Techniques:** Clustering (KMeans, DBSCAN, OPTICS, BIRCH), Heatmaps, Time Series Analysis
- **Visualization:** Folium maps, Scatter plots, Cluster overlays

---


## Introduction

With more than 15 million rides per day across 600 cities in 65 countries, Uber is growing rapidly and leaves an unprecedented impact in this new technological era. It has disrupted multiple industries including ride-sharing and food deliveries. With just an app, individuals can order their dinner or catch a ride to the airport, and as of 2019, 36 percent of US adults stated that they had used a ride-hailing app. As of today, there are approximately one million Uber drivers in the US, relying on this service for income. 

It is easy to see how Uber creates convenience in people’s lives and will continue to grow especially in bigger metropolitan areas, such as New York City. Once dominated by yellow taxis, NYC has shifted to hailing rides mostly through Uber and Lyft. Additionally, with hundreds of thousands of pickups a month, it may be difficult to navigate the city as an Uber driver trying to find the most amount of pickups. In this project, the team members will analyze a dataset on Uber pickups in the New York City Metro Area found on Kaggle. This dataset describes the time and date of the pickup with latitude and longitude information. This data will allow visualization of most common pickup spots through scatterplots and heatmaps, and also allow individuals to understand the best pickup times depending on day of the week through similar methods. 

The machine learning algorithms used in this project are K-Means Clustering, DBSCAN, and OPTICS which will help identify different clusters that are popular pickups in NYC and give drivers an idea on where to drive to for the best outcome. Analyzing and visualizing the data will also help Uber improve its business model and decision-making skills.

## Description of Dataset

The dataset was retrieved from Kaggle datasets that has information on Uber pickups in the New York City Metro Area. This directory contains data on over 4.5 million Uber pickups in New York City from April to September 2014, and 14.3 million more Uber pickups from January to June 2015. However, for the sake of this iteration of the project, only the data from April 2014 was used, with over 500,000 lines of data. The features in this dataset are Date/Time, Latitude, Longitude, Base. I am not using Base for the sake of this experiment. Additionally, the data from January to June 2015 does not provide Latitude and Longitude data, so it will not be used in future experiments.


## 📈 Visualization

![image](https://github.com/user-attachments/assets/e3071d86-b5b4-4f46-906f-b2ba295954a6)

![image](https://github.com/user-attachments/assets/75fc1469-3993-481d-9644-b98502fc5be1)

![image](https://github.com/user-attachments/assets/162fc857-7989-43e8-8e35-40bbe4989ceb)

## 📈 Key Insights

- 🚗 Most pickups occur in Manhattan, but outer boroughs like Brooklyn show ~10% growth
- ⏰ Peak hours are 5–7 PM on weekdays and after 9 PM on weekends
- 🗺️ DBSCAN and OPTICS identified denser clusters in nightlife and tourist zones








