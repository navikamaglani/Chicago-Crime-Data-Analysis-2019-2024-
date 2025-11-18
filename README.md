# **Chicago Crime Data Analysis (2019–2024)**

This project analyzes crime trends in Chicago between 2019 and 2024 using the Chicago Crime Dataset.  
The objective was to uncover temporal, geographic, and categorical crime patterns through data preprocessing, exploratory visualization, clustering, and an interactive Tableau dashboard.

---

## **1. Project Overview**

The project focuses on:

- Understanding citywide crime distribution  
- Identifying hotspots and high-risk locations  
- Analyzing crime frequency by time, location, and category  
- Studying the impact of events such as COVID-19 and 2021 riots  
- Building an **interactive, multi-filter Tableau dashboard**  

---

## **2. Dataset Overview**

The dataset includes:

- **ID & Case Number** – unique identifiers  
- **Date & Time** – used for temporal analysis  
- **Primary Type & IUCR Code** – crime category and classification  
- **Arrest & Domestic** – flags for law enforcement response  
- **District, Ward, Community Area** – administrative boundaries  
- **Latitude & Longitude** – used for mapping and hotspot analysis  

---

## **3. Methodology**

### **3.1 Data Preprocessing**
- Cleaned and standardized date fields  
- Handled missing values  
- Extracted **Direction** and **Street Name** from location descriptions  
- Grouped 36 crime types into **7 major categories** for clarity  
- Created calculated fields for:
  - Crime Type Groups  
  - Directions  
  - Arrest Percentage  
  - Year filters  

---

### **3.2 Exploratory Visualizations**
Key techniques:

- Crime frequency plots  
- Time-series trend analysis  
- Geographic mapping  
- Category distribution charts  
- Heatmaps for crime timing  
- Dual-axis charts comparing crime count & arrest rate  

---

### **3.3 Tableau Dashboard**
We built a **fully interactive dashboard** with filters for:

- Year  
- Crime Category  
- Location Direction  
- Street Name  

Dashboard Components:

- **Heat Map** – crimes by hour vs. weekday  
- **Donut Chart** – crime distribution by category  
- **Dual Axis Trend Chart** – total crimes vs arrest rate  
- **Geospatial Maps** – crime hotspots by community area  

---

## **4. Key Findings**

- **Crime Hotspots:** Central/Downtown areas had the highest crime density  
- **Peak Times:** Evenings and weekends show higher crime frequency  
- **Crime Types:** Property crimes were the most frequent category  
- **COVID-19 Impact:** Reported crimes dipped in 2020, rebounded in 2021  
- **Post-Riot Policy Impact:** Arrest rates increased in 2021–2022  
- **College Areas:** Lower crime frequency near major universities  
- **School Breaks:** Crime dips during summer and winter school breaks  

---

## **5. My Contribution (Navika Maglani)**

I contributed the following:

- **Sourced and cleaned the Chicago crime dataset**  
- Developed the **storyline and structure** for the dashboard  
- Designed visualizations highlighting:
  - Crime trends  
  - Crime categories  
  - Comparative year-over-year changes  
- Grouped 36 crime types into major categories  
- Prepared documentation explaining:
  - Visualization design  
  - Interactivity choices  
  - Data transformations  
  - Key crime insights  

This clearly separates my contribution from the team deliverables.

---

## **6. Tools & Technologies**

- **Python (Pandas)** – initial cleaning & preprocessing  
- **Tableau** – dashboards and interactive visualization  
- **Geospatial Mapping** – latitude/longitude hotspot analysis  
- **Time Series Analysis** – trend exploration  
- **Categorical Grouping** – crime type simplification  

---

## **7. Future Work**

- Integrate external datasets (weather, socioeconomic indicators)  
- Add predictive modeling for crime risk forecasting  
- Include anomaly detection for sudden spikes  
- Expand dashboard with deeper drill-down features  

---

## **8. Repository Structure**

```
chicago-crime-analysis/
│
└── README.md
```

(Note: The dataset is not included due to size and licensing constraints.)

---
## 🔗 Tableau Dashboard Access

This project includes an interactive Tableau dashboard for exploring Chicago crime trends.

The dashboard is hosted on Tableau Public by my teammate:

**Chicago Crime Data Analysis — Tableau Dashboard**  
Hosted by: **Charan Mohitay**  
Link:https://public.tableau.com/app/profile/charan.mohitay7733/viz/ChicagoCrimeDataAnalysis_17418125763000/Dashboard2?publish=yes

📌 **Note:**  
This was a group project. The dashboard is hosted under my teammate’s Tableau profile, but the analysis, data preprocessing, and visualization design include contributions from all team members.  
My individual contributions are clearly outlined in the section above.


