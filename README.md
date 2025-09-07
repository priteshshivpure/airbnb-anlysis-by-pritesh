# 🏠 Airbnb Data Analysis Project

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-yellow.svg)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-lightblue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-red.svg)
![Geopandas](https://img.shields.io/badge/GeoPandas-Geospatial-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

A comprehensive analysis of **Airbnb listings data**, exploring **pricing trends, availability patterns, sentiment analysis, and neighborhood influences** using Python data science tools.

---

## 📌 Table of Contents
- [🌟 Project Overview](#-project-overview)
- [✨ Features](#-features)
- [📂 Dataset](#-dataset)
- [🛠️ Technologies Used](#️-technologies-used)
- [📂 Project Structure](#-project-structure)
- [💻 Installation](#-installation)
- [🚀 Usage](#-usage)
- [📌 Key Findings](#-key-findings)
- [📈 Results](#-results)
- [🔮 Future Work](#-future-work)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)
- [📬 Contact](#-contact)

---

## 🌟 Project Overview
This project aims to **analyze Airbnb open data** to uncover insights about:
- 🏘️ Pricing trends across neighborhoods and property types  
- 📅 Seasonal availability patterns  
- 🛋️ Relationship between amenities and pricing  
- 🌍 Geospatial distribution of listings  
- 💬 Guest review sentiment and its impact on bookings  

---

## ✨ Features
- **Data Cleaning Pipeline** → Handle missing values, outliers, and normalization  
- **Exploratory Data Analysis (EDA)** → Discover relationships in the data  
- **Machine Learning Models** → Predict Airbnb listing prices  
- **Geospatial Analysis** → Property mapping & hotspot detection  
- **Sentiment Analysis** → Review text analysis and ratings correlation  
- **Interactive Dashboards** → Plotly-based dynamic reports  

---

## 📂 Dataset
The analysis uses Airbnb’s **open dataset** from [Inside Airbnb](http://insideairbnb.com/get-the-data.html), including:
- **Listings data** → Property details, amenities, and prices  
- **Reviews data** → Guest comments, ratings, and dates  
- **Calendar data** → Availability & price changes over time  

📌 Place raw datasets inside the `data/raw/` directory.  

---

## 🛠️ Technologies Used
- **Python** (3.8+)  
- **Pandas**, **NumPy** – Data manipulation  
- **Matplotlib**, **Seaborn** – Visualization  
- **Plotly** – Interactive dashboards  
- **Scikit-learn** – Machine learning  
- **Geopandas** – Geospatial analysis  
- **Jupyter Notebook** – Development environment  

---

## 📂 Project Structure
airbnb-analysis/
├── data/
│ ├── raw/ # Original datasets
│ └── processed/ # Cleaned and transformed data
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ ├── 02_eda.ipynb
│ ├── 03_price_prediction.ipynb
│ └── 04_sentiment_analysis.ipynb
├── src/
│ ├── data_processing.py
│ ├── visualization.py
│ └── models.py
├── results/
│ ├── figures/ # Generated visualizations
│ └── insights/ # Analysis findings
└── README.md

## 📈 Results

The analysis produced:

🗺️ Geospatial maps of price distribution

📊 Amenity importance charts

📅 Availability calendars

💬 Review sentiment analysis

🤖 Machine learning price prediction metrics
