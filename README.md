# 🚀 Advanced Data Analysis: Spotify Listening Trends Dashboard (Power BI, DAX, Data Modeling)

## 🎯 Project Value Proposition

This repository showcases an end-to-end **Power BI** project focused on **Spotify Listening Data Analysis** (2013–2024). It demonstrates proficiency in the full **BI lifecycle**, including **Data Cleaning, Dimensional Modeling, DAX formula creation, and dynamic KPI dashboard development**. The project delivers critical **user behavior insights** through advanced visualizations like **Heat Maps** and **Quadrant Analysis**, making it a strong portfolio piece for roles in **Data Analytics, Business Intelligence (BI Developer)**, and **Data Science**.

---

## 🛠️ Key Skills & Technologies Demonstrated

| Category | Skills & Tools |
| :--- | :--- |
| **Business Intelligence** | **Power BI**, Dashboard Design, Reporting, Data Storytelling |
| **Data Analysis & Modeling** | **Dimensional Modeling** (Star Schema focus), **KPI Development**, Data Validation, ETL/ELT Process |
| **Calculation Engine** | **DAX** (Time Intelligence, Complex Measures, Ratio Calculations, Filtering) |
| **Data Visualization** | **Heat Maps**, **Scatter Plots**, Quadrant Analysis, Dynamic Filtering, Drill-Through Functionality |
| **Behavioral Analytics** | Skip Rate Analysis, Session Analysis, User Engagement Metrics |

---

## 📊 Quantifiable Results & Key Performance Indicators (KPIs)

The dashboard provides the following quantifiable metrics, analyzing listening behavior across 11 years of data:

| KPI | Metric | Context / Analytical Achievement |
| :--- | :--- | :--- |
| **Total Track Played** | 150K | Volume of user consumption over the analysis period. |
| **Total Listening Hours** | 5,341.54 | Measures total user engagement time. |
| **No of Albums** | 7,907 | Content diversity metric. |
| **No of Artist** | 4,112 | Measures artist discovery and catalog breadth. |
| **No of Tracks** | 13,665 | Measures track diversity. |
| **Repeat Rate %** | 90.88 % | High-level user loyalty metric. |
| **Shuffle Ratio %** | 74.46 % | Measures preference for curated vs. randomized playback. |
| **Skip Ratio %** | 5.25 % | Crucial content engagement/drop-off metric. |

---

## 📈 Dashboard Features & Analytical Deep Dive

The Power BI report is structured across three functional pages:

### 1. Spotify Overview
Focuses on high-level trends and content performance:
* **Temporal Analysis:** Tracks performance trends for Albums, Artists, and Tracks by Year.
* **Behavioral Segmentation:** Identifies listening patterns across **Weekday & Weekend** distribution.
* **Engagement Metrics:** Includes **Skip Ratio by Album, Artist, and Track** to identify underperforming or over-saturated content.
* **Content Ranking:** Displays Top 5 performing Albums, Artists, and Tracks.

### 2. Listening Patterns
Explores temporal and deep-engagement behaviors:
* **Time-of-Day Analysis (Heat Map):** Visualizes peak listening times across hours (0-23) and days (Mon-Sun) to identify optimal user activity windows.
* **Track Engagement Quadrant Analysis (Scatter Plot):** Categorizes tracks based on frequency (Plays) vs. duration (`ms_played`) to isolate high-value content:
    * **High Frequency & High Listening Time:** *The Most Engaging Tracks.*
    * **Low Frequency & High Listening Time:** *Niche/Deep Catalog Tracks.*
    * **High Frequency & Low Listening Time:** *Short, Repeated Content.*

### 3. Details Grid View (Data Interrogation Layer)
A utility page for auditors and analysts needing granular data access:
* **Interactive Grid:** Displays essential raw fields (Album Name, Artist Name, Track Name).
* **Drill Through & Export:** Features **Drill Through functionality** from any main visual, with the capability to **Export data to CSV**.
* **Hierarchical Navigation:** Supports **Drill Down, Drill Up, and Hierarchy** for flexible data slicing.

---

## 📄 Data Dictionary & Terminology

A detailed data dictionary (**Spotify Analysis Data Terminologies**) defines the data model inputs, including behavioral flags crucial for this analysis:
* `spotify_track_uri`, `ts` (Timestamp), `ms_played` (Playback Duration)
* **Behavioral Fields:** `reason_start`, `reason_end`, `shuffle`, and the core metric driver: **`skipped`**.

---

## Principal Visualizations

<img width="1202" height="798" alt="image" src="https://github.com/user-attachments/assets/df7a47d8-a59c-4095-90bb-78d909cdd6a5" />

<img width="1200" height="801" alt="image" src="https://github.com/user-attachments/assets/4c35926e-0e66-41ac-856c-3449be8a4f08" />

<img width="1184" height="791" alt="image" src="https://github.com/user-attachments/assets/9a1421ca-4c99-4f67-afad-9c2db3125f05" />


## How to Set Up and Run the Dashboard


### Power Bi
 1. Clone this repository  
   ```bash  git clone https://github.com/AmeeJoshi-MCA/Social-Media-Ad-Performance.git```
 
 2. Place Data Files: Ensure the four required .csv files (ad_events.csv, ads.csv, campaigns.csv, users.csv) are placed in the same folder as the .pbix file.

 3. Open the [file](https://github.com/AmeeJoshi-MCA/Social-Media-Ad-Performance/blob/main/PowerBi/SocialMediaAdPerformance.pbit) in Power BI Desktop.

 4. Refresh Data:  If the data doesn't load immediately, go to the Home tab and click Refresh to load the data from the CSV files.
                   (The Power Query steps assume the CSV  files are in the same directory as the PBIX file).


## 🏁 Conclusion

This **Spotify Listening Analysis** project successfully transforms raw streaming data into actionable business intelligence. It serves as a comprehensive demonstration of expertise in **Power BI**, **complex DAX modeling**, and translating nuanced **user behavior data** into clear, segmented insights. This foundation is readily adaptable to similar time-series and behavioral data challenges in e-commerce, finance, or marketing analytics.
