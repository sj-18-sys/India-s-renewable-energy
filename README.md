# India's Renewable Energy Dashboard ⚡

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)](https://www.python.org/)
[![Tableau Public](https://img.shields.io/badge/Visualized%20with-Tableau-orange)](https://public.tableau.com/app/profile/shreejhani.s/viz/Book3_17529556525700/Dashboard1)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A data analytics project exploring India’s renewable energy capacity across states and sources using Python (Pandas, Plotly) and Tableau. The project aims to understand trends, state-wise contributions, and source-wise dominance from available government datasets.

---

## 📑 Table of Contents

- [Project Structure](#project-structure)
- [Usage](#usage)
- [Key Findings](#key-findings)
- [Data Sources](#data-sources)
- [Tech Stack](#tech-stack)
- [Visualization](#visualization)

---
## Project Structure
.
├── renewable_energy.ipynb       # Main analysis notebook
├── renewable_data.csv           # Cleaned and processed dataset
├── LICENSE
└── README.md                    # This file

##  Usage
-- Open the Jupyter Notebook:
**jupyter notebook renewable_energy.ipynb**

**The notebook walks through:**
--Importing and cleaning data
--Melting and reshaping for state/year/source-wise analysis
--Plotting trends using Plotly Express
--Exporting CSVs for use in Tableau

## Key Findings
-- Top contributors: Tamil Nadu, Karnataka, Maharashtra, Gujarat lead in total installed renewable energy capacity.

-- Dominant sources: Wind and solar dominate across most states, while others contribute marginally.

-- Growth trends: Steady increase in capacity, especially in solar installations in the last decade.

-- Disparities: Northeastern states lag behind in adoption, highlighting regional imbalances.

## Data Sources
-- MNRE (Ministry of New and Renewable Energy)

-- Government of India’s open energy datasets

-- India Energy Dashboard

-- Cleaned CSV: renewable_data.csv

## Tech Stack

- **Python**
- **Pandas** – data cleaning & manipulation
- **Matplotlib** and **Seaborn** – data visualization
- **Jupyter Notebook** – for code execution and analysis
- **Tableau Public** - data visalizations

---

##Visualizations

### 1. **State-wise Energy Capacity trend**
- **Type:** Line Plot
- <img width="1413" height="525" alt="newplot" src="https://github.com/user-attachments/assets/49ceb800-d048-470a-9faf-ab421d67ca99" />


### 2. **Top 5 states per energy type**
- **Type:** Bar Plot
- <img width="1413" height="525" alt="newplot (1)" src="https://github.com/user-attachments/assets/de4b6e06-8802-4a10-a0ce-1ab5ceb375a3" />


### 3. **Correlation heatmap**
- **Type:** Stacked Bar Plot / Aggregate Sum
- <img width="954" height="871" alt="image" src="https://github.com/user-attachments/assets/bac58eae-6236-468f-b02c-ac25aabaa154" />
  Theory behind the heatmap:
  Economic Factor: GSDP is the strongest driver for biomass and wind energy development.

  Population: Has a decent connection to biomass but weak for solar and wind — meaning population alone isn't pushing solar/wind capacity.

  Energy Mix Strategy: States excelling in wind also focus on solar, suggesting policy or geographic synergy.
- Insights:
The correlation analysis reveals that economic strength (GSDP) is a significant enabler of renewable energy capacity, particularly for biomass and wind power. Population size shows moderate influence, especially on biomass due to resource availability. States with established wind energy infrastructure also tend to invest in solar, indicating a holistic renewable energy strategy. Policies aiming to enhance GSDP in lower-income states could indirectly boost their renewable energy adoption


### India's Renewable Energy Landscape: 2006–2024
To make the dataset usable for visualizations and analysis, I reshaped it using pandas.melt().
This transformed the data from wide format (years as columns) to long format, with:
- Region and State/UT retained as identifiers
- Year becoming a new column
- Capacity (MW) holding the corresponding values

This dashboard explores India's renewable energy capacity trends from 2006 to 2024. It includes:

  --The top 10 states by installed capacity(MW)

  --An India map breakdown by energy type 

  --Zone-wise capacity analysis across the country

  --Year-wise growth trends by energy type
>> [View the Dashboard](https://public.tableau.com/views/Book3_17529556525700/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
<img width="1666" height="822" alt="Screenshot 2025-07-20 013600" src="https://github.com/user-attachments/assets/61498c8e-c434-4dee-aa33-6f42be4b6cdb" />


Filter by zone, energy type, and year to dive deeper into regional contributions and national progress toward sustainable energy goals.
---


