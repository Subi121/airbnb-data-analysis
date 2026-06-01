# 🏠 Airbnb Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-9cf)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

An Exploratory Data Analysis (EDA) project on Airbnb listings across New York City using Python, Pandas, and Matplotlib. Analyzes pricing trends, neighbourhood patterns, room type distributions, host activity, cancellation policies, and availability insights across **102,599 listings** from **2003 to 2022**.

---
 
## 🎯 Objective
 
- Analyze pricing trends across NYC boroughs and room types
- Identify top hosts, neighbourhoods, and listing patterns
- Understand how cancellation policies affect availability
- Explore correlations between reviews, pricing, and host verification
- Derive actionable insights from 102,599 listings spanning 2003–2022
---

## 📁 Dataset

| Property | Value |
|---|---|
| Records | 102,599 |
| Columns | 26 |
| Coverage | 2003 – 2022 |
| Country | United States |
| Price Range | $50 – $1,200 |
| Fields | ID, Name, Host ID, Host Name, Host Verified, Neighbourhood Group, Neighbourhood, Latitude, Longitude, Country, Instant Bookable, Cancellation Policy, Room Type, Construction Year, Price, Service Fee, Minimum Nights, Number of Reviews, Last Review, Reviews per Month, Review Rate, Host Listings Count, Availability 365, House Rules, License |

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

---

## 📂 Project Structure
 
```
airbnb-data-analysis/
├── Airbnb Dataset.xlsx             # Dataset file
├── Airbnb_Data_Analysis.ipynb      # Main analysis notebook
├── requirements.txt                # Python dependencies
└── README.md
```

---

## 📊 Analysis & Visualizations

| Chart | Description |
|---|---|
| Room Type Distribution | Count of listings across 4 types — Private Room, Entire Home/Apt, Shared Room, Hotel Room |
| Listings by Neighbourhood Group | Manhattan (43,792) and Brooklyn (41,842) dominate the NYC listing count |
| Average Price by Neighbourhood Group | Bar chart comparing average nightly price across all 5 NYC boroughs |
| Top 5 Most Active Hosts | Michael leads with 881 listings, followed by David (764) and John (581) |
| Price Distribution Histogram | Frequency of prices ($50–$1,200) with median marker at $624 |
| Min Nights by Room Type | Average minimum stay required per room type |
| Price vs. Review Rating | Average price grouped by review score (1–5) |
| Availability by Cancellation Policy | How strict / moderate / flexible policies affect days available per year |
| Price Trend by Construction Decade | Line chart of average price across property build years (2003–2022) |
| Price by Host Verification Status | Verified vs. unverified host pricing comparison |
| Price vs. Reviews Per Month | Scatter plot showing correlation between review frequency and price |
| Top 5 Most Expensive Neighbourhoods | Neighbourhoods with highest average price (min. 10 listings) |

---

## 🔍 Key Insights

* **Manhattan** has the highest number of listings (43,792) and commands the highest average nightly prices among all NYC boroughs
* **Entire Home/Apt** is the most common room type, followed closely by Private Room
* **Michael** is the most active host with 881 listings — a small group of power hosts dominates the platform
* Price range spans **$50 to $1,200** with a median of **$624**, indicating a right-skewed distribution with premium outliers
* All listings are based in the **United States**, specifically New York City across 5 borough groups
* **Flexible cancellation policies** are associated with significantly higher annual availability compared to strict policies
* Guest review ratings range from **1 to 5**, with most listings clustering at 4–5 stars

---

## 🚀 Run the Project

```bash
git clone https://github.com/Subi121/airbnb-data-analysis.git
cd airbnb-data-analysis
pip install -r requirements.txt
jupyter notebook Airbnb_Data_Analysis.ipynb
```

Or open directly in **Google Colab**:

1. Open the notebook **Airbnb_Data_Analysis.ipynb** in **Google Colab**
2. Upload `Airbnb Dataset.xlsx`
3. Run all cells to generate charts and insights

---

## 🔭 Future Improvements

* Sentiment analysis on listing names and house rules
* Predict listing price using ML regression models (Ridge, XGBoost)
* Build an interactive dashboard using Plotly or Streamlit
* Add geospatial heatmap of listings and pricing using Folium

---

## ⚠️ Disclaimer
* This is an independent data analysis project completed during an internship at **VOIS (Vodafone Intelligent Solutions)**.  
* Not affiliated with or endorsed by Airbnb, Inc.  
* Dataset was provided as part of the internship program

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
