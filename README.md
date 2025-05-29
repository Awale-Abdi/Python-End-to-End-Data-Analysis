<h1 align="center">Los Angeles Crime Trends (2020–2023): A Python-Powered Public Safety Analysis</h1>

## 📊 Overview
This project analyzes crime trends in the City of Los Angeles using publicly available LAPD datasets covering 2020 through early 2023. It uses Python and key libraries like pandas, matplotlib, seaborn, and plotly to explore temporal, geographic, and demographic crime patterns. Originally completed as a group assignment, this standalone version was fully restructured, reinterpreted, and replicated by me using a reproducible Jupyter Notebook.

The analysis processes 843,000+ crime records across 28 features (≈180MB), showcasing my ability to handle real-world, large-scale datasets without SQL or cloud infrastructure. The project combines full-cycle data cleaning, statistical hypothesis testing, and rich visual storytelling to uncover actionable insights on when, where, and how crimes occur in LA.

## 📌 Key Questions Explored
1. **Temporal Trends** – How do crime patterns vary by year, month, and day of the week?
2. **Hotspots** – Which neighborhoods or coordinates report the most incidents?
3. **Crime Type & Weapon Use** – What are the most common offenses and are weapons involved?
4. **Demographics (when available)** – Are certain groups disproportionately impacted?
5. **COVID-19 Impact** – Did 2020–2021 show unique spikes or drops in activity?

## 🧠 Methodology

- **Language**: Python (Jupyter Notebook)
- **Libraries**: `pandas`, `matplotlib`, `seaborn`, `plotly`, `scipy.stats`
- **Dataset**: [Crime Data from 2020 to Present – LAPD Open Data Portal](https://data.lacity.org)
- **Approach**:
  - Imported and cleaned raw CSV data (~270MB)
  - Handled missing values, date formatting, and category normalization
  - Generated descriptive and inferential statistics
  - Performed hypothesis testing on temporal and spatial crime patterns
  - Created both static and interactive visuals

## ⚙️ Project Highlights

- Cleaned and prepared 500K+ crime reports across over 120 variables.
- Built exploratory visuals on yearly/monthly trends, geographic clustering, and peak crime days.
- Hypothesis tested for significance in trends like:
  - Day-of-week impact on crime frequency
  - Location-based crime density
- Used heatmaps, histograms, bar graphs, and scatterplots to highlight key findings.

## 📁 Project Structure

- `Datasets/`  
  - `Crime_Data_from_2020_to_Present.csv` – unprocessed original crime data

- `Outputs/`  
  - `Crimes in Los Angeles.ipynb` –  cleaned, analyzed, and visualized dataset with key insights 

## 🧩 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Large dataset with missing/mislabeled fields | Standardized column types, dropped NAs where justified |
| Coordinates had outliers | Filtered to valid LA geobounds |
| Crime codes needed contextual translation | Mapped codes to descriptions using LAPD metadata |
| COVID-19 impact skewing trends | Analyzed 2020 separately to control for anomaly |

## 📈 Sample Insights

- **Crime peaked in 2022**, with ~150K+ incidents, showing recovery after 2020 dip.
- **Friday and Saturday** saw the highest crime rates, while **Sunday and Tuesday** were lowest.
- **Downtown LA, Hollywood, and South LA** consistently reported the most crimes.
- **Assaults and vehicle-related crimes** dominated, with increasing reports of weapon usage post-2021.
- No direct causality proven, but visual correlations suggest post-lockdown spikes.

## 🔗 Data Source

- [LAPD Crime Data Portal](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8)

---

### **Contact**

For inquiries, collaborations, or feedback:

- 📧 Awaleiabdi@outlook.com  
- 💼 [LinkedIn – Awale Abdi](https://www.linkedin.com/in/awale-abdi/)
