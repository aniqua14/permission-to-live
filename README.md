# 🏥 Permission to Live

A data investigation into women's healthcare inequality across Bangladesh using real national survey data.

> *"In Bangladesh, a woman's health is not just determined by disease. It is determined by where she was born, how educated she is, and whether someone will give her permission to see a doctor."*

![Dashboard Preview](Permission_to_Live_Dashboard.png)

---

## 🔗 Project Files

- 📓 `BD_Health_Atlas_Project1.ipynb` — Full Python analysis notebook
- 📊 `Permission_to_Live_Dashboard.pbix` — Interactive Power BI dashboard with division slicer and KPI cards
- 🗺️ `bangladesh_health_map.html` — Interactive choropleth map (open in browser)
- 📁 CSV files — Cleaned and aggregated datasets

---

## 🔍 Key Findings

- 🔴 **Chattogram** has the highest permission barrier — 35% of women need permission to access healthcare
- 🟢 **Khulna** performs best overall — lowest barriers across all categories
- ⚠️ **Permission is the #1 barrier** — bigger than distance or safety concerns, in every single division
- 💰 Even the **richest women** face a 24.3% permission barrier — proving this is a **gender problem, not just a poverty problem**
- 📚 **Sylhet and Mymensingh** have the highest female no-education rate at 18.1%
- 🏙️ Rural women face **7% more permission barriers** than urban women
- 👩 **30,078 women** surveyed across **8 divisions** — BDHS 2022

---

## 🧠 What This Project Investigates

This project analyzes three core questions using the Bangladesh Demographic and Health Survey (BDHS) 2022:

1. **Which divisions leave women most vulnerable** in terms of education and healthcare access?
2. **Does wealth protect women** from healthcare barriers?
3. **Is the barrier physical (distance) or social (permission)?**

---

## 📊 Visualizations

| Chart | Description |
|-------|-------------|
| `education_inequality.png` | Women with no education vs higher education by division |
| `healthcare_barriers.png` | Three types of barriers faced by women across divisions |
| `wealth_vs_healthcare.png` | How wealth level affects healthcare access barriers |
| `urban_rural_barriers.png` | Urban vs rural comparison of all three barriers |

---

## 🗂️ Project Structure

- `BD_Health_Atlas_Project1.ipynb` — Full analysis notebook with explanations
- `Permission_to_Live_Dashboard.pbix` — Power BI source file
- `Permission_to_Live_Dashboard.pdf` — Dashboard PDF export
- `bangladesh_health_map.html` — Interactive Folium map
- `division_summary.csv` — Key indicators per division
- `barriers_by_division.csv` — Healthcare barrier scores per division
- `wealth_barriers.csv` — Barrier analysis by wealth level
- `urban_rural.csv` — Urban vs rural barrier comparison
- `edu_by_division.csv` — Education levels by division
- `women_clean.csv` — Cleaned individual women's dataset
- `*.png` — All saved chart visualizations

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Python (pandas, seaborn, matplotlib) | Data cleaning, analysis, visualization |
| Folium | Interactive geographic map |
| Power BI Desktop | Interactive dashboard |
| BDHS 2022 | Primary data source |

---

## 📂 Data Source

**Bangladesh Demographic and Health Survey (BDHS) 2022**
- Conducted by NIPORT, Ministry of Health and Family Welfare
- Sample size: 30,078 women across all 8 divisions
- Accessed via: [dhsprogram.com](https://dhsprogram.com)

> ⚠️ Raw DHS data files are not included in this repository as per DHS Program data sharing conditions. Request access at dhsprogram.com.

---

## 💡 Honest Note

This project uses survey-reported data. Healthcare barrier questions were only asked to women who had sought healthcare in the past 12 months — meaning the actual barriers faced by women who never sought healthcare at all may be even higher than reported here.

---

## 👩 Author

**Aniqua Nawar** — Data Analytics Portfolio Project
University of Liberal Arts Bangladesh
[GitHub](https://github.com/aniqua14)
