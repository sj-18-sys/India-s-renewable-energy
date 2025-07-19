# 🌱 India's Renewable Energy Analysis

This project explores the growth and distribution of renewable energy sources across India. Using public data and Python, we visualize trends in solar and wind energy adoption at both national and state levels, uncovering insights into India's green energy transition.

---

## 📂 Dataset

The data is sourced from:
- **Kaggle**
- Includes state-wise solar and wind capacity (in MW) over several years

---

## 🛠️ Tools and Libraries

- **Python**
- **Pandas** – data cleaning & manipulation
- **Matplotlib** and **Seaborn** – data visualization
- **Jupyter Notebook** – for code execution and analysis
- **Tableau Public** - data visalizations

---

## 📊 Key Visualizations

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


