# 🦠 The Evolution of COVID-19 in New York State: A Visual Timeline

This project presents a data-driven visualization and analysis of how COVID-19 evolved across New York State, focusing on the interplay between healthcare infrastructure, vaccination rollout, and demographic impact.

## 📊 Analysis 1: First Dose across New York

The first analysis visualizes the **distribution of first-dose COVID-19 vaccinations** across counties in New York State. Using Tableau's geographic mapping capabilities, this view highlights the cumulative number of first doses administered in each region. Key insights include:

- **High concentration** of vaccinations in densely populated counties like Kings and Queens.
- **Lower uptake** in certain upstate counties, possibly due to accessibility issues or population density.
- **Tooltip interactivity** enables on-hover access to exact values for each county.

> 📍Example Insight:  
> *Broome County* received **812,520** first doses — a key data point reflecting regional vaccine outreach efforts.

This map serves as a foundational layer for understanding how vaccination rollouts varied geographically and how these differences may relate to hospitalization and mortality trends in later stages of the pandemic.

---

## 📁 Project Overview

### 🔍 Objective
To analyze the relationships between **patient demographics**, **healthcare capacity**, and **vaccination efforts** on COVID-19 outcomes in New York State.

### 🎯 Goals
- Understand how **age**, **ICU availability**, and **vaccination rates** influenced **hospitalization** and **mortality**.
- Generate visual and statistical evidence to inform future **public health policy**.

### 📈 Hypotheses
- Older adults (65+) are more vulnerable to hospitalizations and deaths.
- Higher vaccination rates reduce ICU occupancy (e.g., in Queens County).
- Positive correlation between confirmed cases and fatalities.
- No strong correlation between first dose and next-quarter hospitalizations.
- Higher staffed acute care beds → more patient discharges.

---

## 🧰 Tools & Tech Stack

| Category          | Tools Used                 |
|------------------|----------------------------|
| Data Cleansing   | Python (NumPy, Pandas)     |
| Visualization    | Tableau                    |
| Dataset Sources  | New York State Open Data   |

---

## 📚 Data Sources

- [COVID-19 Hospitalizations](https://health.data.ny.gov/Health/New-York-State-Statewide-COVID-19-Hospitalizations/jw46-jpb7/data_preview)  
- [COVID-19 Testing (Archived)](https://health.data.ny.gov/Health/New-York-State-Statewide-COVID-19-Testing-Archived/xdss-u53e/data_preview)  
- [COVID-19 Vaccination Data](https://health.data.ny.gov/Health/New-York-State-Statewide-COVID-19-Vaccination-Data/duk7-xrni/data_preview)  

---

## 🧑‍🤝‍🧑 Team Members

- Bhoomi Parikh  
- L. Sameera Velama  
- Matiullah Mati  
- Ramya P. Jandhyala  
- Vikramaditya Devarakonda

---

## 🎥 Demo

A short walkthrough of our Tableau dashboard and insights can be found in the [Video Demo](./DataVizProject.mp4).

---

Stay tuned as we add more insights from hypotheses and visualizations!

## 📊 Analysis 1: First Dose Across New York

This visualization illustrates the total number of **first-dose COVID-19 vaccinations** administered per county across New York State. Using Tableau’s geo-mapping, each county is color-coded based on the volume of vaccinations, enabling easy comparison across regions.

### 🧠 Key Observations:
- **Urban counties** like Kings, Queens, and Bronx show **significantly higher** vaccination counts, aligning with their population density.
- **Rural areas** such as Allegany and Delaware counties display **comparatively lower uptake**, possibly due to logistical or demographic factors.
- The interactive tooltips provide specific dose numbers for each county (e.g., *Broome County: 812,520*).

This visualization is foundational in understanding the spread and reach of early vaccination efforts and sets the stage for later analyses on hospitalization, ICU occupancy, and mortality.
