# 🌌 Exoplanetary Systems Analysis | CMSE201 Final Project

## Overview
This project investigates the relationship between **stellar mass** and the **structure of planetary systems**, focusing on the implications for **habitability**. Using the *All Exoplanets Dataset* from **Kaggle**, I explored whether a star's mass correlates with:
1. The number of planets it hosts
2. The presence of potential habitable zones

The project includes:
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Visualizations (scatter plots, boxplots, heatmaps)
- Basic habitability assessment
- Final results and interpretation

---

## Data Source  
The dataset used in this project is from Kaggle:  
📂 [All Exoplanets Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/all-exoplanets-dataset)  
It contains **confirmed exoplanets** and their host star properties up to **2021**.  
This dataset was crucial in helping answer two main research questions:
1. Is there a relationship between stellar mass and the number of planets?
2. Are there planetary systems similar to ours with potential habitable zones?

---

## Approach Summary

### ✅ Data Preparation
- Loaded the Kaggle dataset into Python.
- Selected relevant columns for planetary systems and stellar masses.
- Converted absolute stellar mass to a **solar-relative scale** (i.e., in units of the Sun’s mass).
- Filtered, cleaned, and restructured the data for analysis.

### ✅ Visualizations
- **Boxplot**: Showed distribution of stellar masses across systems.
- **Scatter Plot**: Explored the relationship between mass and planet counts.
- **Heatmap**: Revealed frequency patterns between stellar mass and system multiplicity.

### ✅ Habitable Zone Modeling
- Implemented basic habitable zone formulas to approximate **habitable distances**.
- Identified planetary systems that are likely to have conditions similar to those in our solar system.

### ✅ Results
- Found that stars with masses similar to the Sun are more likely to host **multi-planet** systems.
- Identified **two systems** with planets inside habitable zones.
- Noted that high-mass stars tend to have **fewer planets**, supporting theories about star formation and evolution.

---

## Tools Used
- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualizations
- **Jupyter Notebook**
- **Kaggle** for dataset acquisition

---

## Notes
This project represents a full end-to-end workflow:
- From **data acquisition** (Kaggle)
- To **exploratory data analysis**
- To **interpretation of scientific results**
- All summarized in the attached **PDF report** and demonstrated step-by-step in the notebook.

---

## Credits & References
- [All Exoplanets Dataset (Kaggle)](https://www.kaggle.com/datasets/shivamb/all-exoplanets-dataset)
- [Planetary Biology | Habitable Zones](https://www.planetarybiology.com/calculating_habitable_zone.html)
- [GeeksforGeeks | Data Visualization Tutorials](https://www.geeksforgeeks.org)
- [OpenAI | GPT-4 assistance]
- [Seaborn | Heatmap Example](https://seaborn.pydata.org/examples/spreadsheet_heatmap.html)
- [Habitable Zone Calculator GitHub](https://github.com/Eelt/HabitableZoneCalculator)

---

## 🌟 Personal Reflection
This project challenged me to:
- Apply theoretical data science skills to a **real-world astrophysics problem**
- Balance **data visualization** with **scientific insight**
- Perform **habitability modeling** for the first time
- Gain confidence working with **real astronomical datasets** using Python

---
