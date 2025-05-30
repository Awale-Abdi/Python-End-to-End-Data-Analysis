<h1 align="center">Los Angeles Crime Trends (2020–Present): A Python-Powered Public Safety Analysis</h1>

## 📊 Overview

This solo-developed project explores over **843,000 Los Angeles crime reports** (2020–2023) using **Python-powered data analysis** to uncover when, where, and how crimes occur. Originally a group case study, I fully **replicated and restructured the project independently** in a Jupyter Notebook, applying a structured and reproducible workflow from raw ingestion to insight.

With over **180MB of real-world LAPD data**, this project demonstrates my ability to work with **large-scale datasets**, handle **complex feature engineering**, and conduct **hypothesis-driven public safety analysis**. I hosted the raw CSV on **AWS S3** to ensure accessibility and demonstrate end-to-end thinking beyond GitHub’s file size limits.

The project blends **data cleaning, geospatial mapping, statistical testing**, and **visual storytelling**—showcasing practical skills in both **data science** and **civic analytics**.

---

## 📌 Key Business Questions Answered

1. **What are the major crime trends by year, month, and day?**  
2. **Where do crimes cluster across Los Angeles?**  
3. **Which crime types dominate, and how often are weapons involved?**  
4. **How do age, sex, and other demographics affect crime patterns?**  
5. **What effect did COVID-19 have on public safety metrics?**

---

## 🧠 Technical Approach

- **Tools & Stack**:  
  `Python`, `pandas`, `seaborn`, `matplotlib`, `plotly`, `folium`, `scipy.stats`, `Jupyter Notebook`
  
- **Data Source**:  
  LAPD Open Data Portal – [Crime Data from 2020 to Present](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data)

- **Core Techniques**:
  - Cleaned and transformed 28-column dataset across 843,000+ rows
  - Performed exploratory data analysis and feature extraction (date, location, demographics)
  - Applied statistical tests (e.g., t-tests, z-tests) to validate temporal and spatial trends
  - Created **custom null-value diagnostic functions** to visualize data quality
  - Built interactive heatmaps and visual dashboards for geographic insights

---

## ⚙️ Project Highlights

- 🧹 Cleaned & preprocessed **500K+** valid crime entries after filtering invalid/missing data  
- 📈 Built visual analyses covering:
  - **Temporal patterns** (year/month/day heatmaps)
  - **Crime type frequency** (top 20 offenses, weapon breakdowns)
  - **Demographics** (age, sex, frequency histograms)
  - **Spatial distribution** using `folium` and `HeatMap`
- ✅ Used reproducible practices like fixed random seed and modular cell blocks  
- 📊 Conducted **statistical testing** on:
  - Weekly crime fluctuations (e.g., Friday–Saturday peaks)
  - Area-level clustering to validate police resource allocation

---

## 📁 Project Structure

- `Datasets/`  
  - `Crime_Data_from_2020_to_Present.csv` – unprocessed original crime data

- `Outputs/`  
  - `Crimes in Los Angeles.ipynb` –  cleaned, analyzed, and visualized dataset with key insights

---

## 🧩 Data Challenges & Smart Fixes

| Problem | Solution |
|--------|----------|
| Missing age/sex/location data | Diagnosed and conditionally excluded |
| Coordinate outliers | Filtered to within **Los Angeles geo-boundaries** |
| Inconsistent crime labels | Mapped using LAPD metadata |
| COVID-19 shock effect | Segmented 2020 as its own trend year |

---

## 🔍 Key Insights

- **Crime peaked in 2022**, showing urban rebound post-2020 lockdown dip  
- **Friday & Saturday** are consistently the most dangerous days  
- **Downtown LA, Hollywood, and South LA** had the highest density of crimes  
- **Battery, burglary, and vandalism** were the most reported offenses  
- **Weapon use increased** in assaults post-2021, possibly linked to pandemic-related stressors  
- Victims aged **20–50** accounted for over 60% of incidents  

---

## 🔑 Why This Project Matters

This project showcases my:

- ✅ Proficiency in **exploratory data analysis (EDA)** and **visual analytics**  
- ✅ Ability to manage and extract insight from **large real-world datasets**  
- ✅ Use of **Python for public interest data science**  
- ✅ Technical depth in **data cleaning, transformation, and reproducibility**  
- ✅ Communication skills through **clear storytelling** and **business-relevant interpretation**

Ideal for roles in:
- **Data Analysis**
- **Public Safety & Urban Analytics**
- **Business Intelligence**
- **Python-based Data Science**

---

## 📬 Contact

Let’s connect or collaborate:

- 📧 Awaleiabdi@outlook.com  
- 💼 [LinkedIn – Awale Abdi](https://www.linkedin.com/in/awale-abdi/)


