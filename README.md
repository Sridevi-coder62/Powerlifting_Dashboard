# Powerlifting Dashboard in Power BI

## 📊 Overview
This project is an interactive Power BI dashboard analyzing **global powerlifting competitions**.  
It combines KPIs, charts, and maps to explore lifter performance, federation comparisons, equipment usage, and competition trends.

---

## 🔹 Features
### Top KPIs
- **Total Competitions:** 8,482  
- **Total Lifters:** 136.69K  
- **Top Wilks Score:** 779.38  
- **Average Total Lifted (Kg):** 398.71  
- **Average Bodyweight (Kg):** 33.33M  

### Visualizations
- **Timeline of Competitions (Line Chart):** Growth of competitions over time.  
- **Top Lifters (Bar Chart):** Ranking athletes by Wilks score.  
- **Equipment Type Distribution (Donut Chart):** Raw vs equipped lifting styles.  
- **Age vs Strength (Scatter Plot):** Relationship between age and total lifted, split by gender.  
- **Federation Comparison (Stacked Bar Chart):** Average Wilks by federation, broken down by equipment.  
- **Federation Share (Pie Chart):** Distribution of competitions across federations.  
- **Meet Locations (Map):** Geographic spread of competitions.  

### Interactive Filters (Slicers)
- **Sex**  
- **Equipment**  
- **Division**  
- **Year**  

---

## 🔹 Dataset
The dashboard is built on a dataset named **`cleaned_powerlifting`**, derived from publicly available powerlifting competition records.  

### Key Fields
- **meetid** → Unique identifier for each competition.  
- **meetname / meetcountry / meetstate / meettown** → Metadata about the competition location and name.  
- **federation** → Organizing federation (e.g., IPF, USAPL, USPA).  
- **name** → Lifter’s name.  
- **sex** → Gender of the lifter (M/F).  
- **age** → Age of the lifter at the time of competition.  
- **bodyweightkg** → Bodyweight in kilograms.  
- **totalkg** → Total weight lifted across squat, bench, and deadlift.  
- **wilks** → Wilks score (performance metric adjusted for bodyweight).  
- **equipment** → Type of lifting style (Raw, Single‑ply, Multi‑ply, etc.).  
- **division** → Competition division (e.g., Open, Juniors, Masters).  
- **year** → Year of the competition.  

### Cleaning & Preparation
- Removed duplicates and invalid records.  
- Standardized schema (consistent column names, units in kilograms).  
- Derived calculated fields (e.g., average Wilks, total lifts).  
- Ensured categorical fields (sex, equipment, federation) were normalized for filtering.  

👉 This cleaned dataset allows for **accurate aggregation, comparison, and visualization** across federations, lifters, and years.

---

## 🔹 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Sridevi-coder62/Powerlifting_Dashboard.git
Open PowerLiftingDashboard.pbix in Power BI Desktop.

Use the slicers to interactively filter by sex, equipment, division, and year.

Explore KPIs, charts, and maps to gain insights into lifter performance and competition trends.

## 🔹 Screenshots
<img width="593" height="341" alt="image" src="https://github.com/user-attachments/assets/cbb70b52-6021-479e-83c2-ea427ddb0edb" />

## 🔹 Insights
Powerlifting competitions have grown significantly since the 1980s.

Most lifters compete raw, though equipped lifting remains present in certain federations.

Strength peaks vary with age, and gender differences are visible in scatter plots.

Federations differ in average Wilks scores, showing competitive strength variations.

Competitions are geographically widespread, with clusters in certain regions.

## 🔹 Future Work
Add drill‑through pages for individual lifter profiles.

Include federation‑level trend analysis.

Enhance visuals with custom themes and tooltips.

## 📌 Author
Created by Sridevi  
Datathon project showcasing Power BI dashboarding, data cleaning, and storytelling.
