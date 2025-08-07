# 📊 Socio-Economic Determinants of Crime

This project investigates how social and economic factors influence crime rates across U.S. states between **2010 and 2023**. It was developed as part of the *Data Visualization* course at the **University of South Florida**.

Crime is a multifaceted societal issue influenced not just by poverty but by broader socio-economic variables like **income levels**, **inequality**, and **unemployment**. This analysis aims to uncover whether predictable patterns emerge between these variables and crime — and whether there's a tipping point where improvements in economic conditions result in significant crime reduction.

Through **state-level data** and interactive **visual storytelling**, this project provides data-driven insights into the economic determinants of crime in the United States.

---

## 🧠 Project Overview

The project focuses on analyzing how the following indicators affect crime rates:

- Median Family Income
- Income Inequality (Gini Index)
- Unemployment Rate
- Poverty Levels

Data was collected from official U.S. Census and FBI sources using Python, cleaned and structured into Excel files, and visualized using **Tableau**. This end-to-end process enabled rich, interactive storytelling across both time and geography.

---

## 🎯 Research Questions & Findings

1. **Is there a specific income threshold beyond which crime rates significantly decline?**
   ✅ Yes. A **$69,000 threshold** was identified, beyond which crime rates stabilize and remain consistently lower. This suggests a potential tipping point where economic well-being translates to public safety.

2. **How does income inequality impact different types of crimes (violent vs. property crimes)?**
   ⚠️ **Violent crimes** show a **steeper increase** with rising income inequality compared to property crimes, indicating that inequality has a stronger impact on more severe offenses.

3. **How do economic indicators such as unemployment rate and poverty affect crime rates?**
   📉 States with **lower poverty and unemployment** levels — especially after 2014 — showed **significant drops in crime rates**, supporting the idea that economic recovery reduces crime.

---

## 📁 Repository Structure
.
├── code/
│   ├── Crime Data.ipynb                          # Extracts and processes crime data from FBI API
│   ├── Economic Data.ipynb                       # Pulls and cleans economic indicators from Census API
│   ├── Gini Data.ipynb                           # Fetches income inequality (Gini Index) from Census API
│   ├── crime_data_2010_2023.xlsx                 # Final crime dataset aggregated by year, state, offense
│   ├── economic_characteristics_2010_2023.xlsx   # Final dataset with income, poverty, and unemployment
│   └── gini_index_2010_2023.xlsx                 # Final dataset with Gini index per state and year
├── Final-Project-GD.pdf                          # Full project report detailing methodology and insights
├── Final-Project-GD.twbx                         # Tableau workbook with interactive dashboard
└── README.md                                     # You're here!

---

## 🛠️ Tools & Technologies

- **Python** – For data extraction and cleaning (FBI Crime Data API, Census Data API)  
- **Jupyter Notebook** – Used to write and run all data scripts  
- **Tableau** – For visual analytics and storytelling dashboard  
- **Excel** – Clean data output for Tableau ingestion

---

## 🔗 Data Sources

The project uses real-time, publicly available data from trusted government sources:

- **Crime Statistics**:  
  📎 [FBI Crime Data Explorer API](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/explorer/crime/query)

- **Economic Characteristics** (DP03 table):  
  📎 [U.S. Census Bureau - Economic Data](https://data.census.gov/table?q=dp03)

- **Income Inequality (Gini Index - B19083 table):**  
  📎 [U.S. Census Bureau - Gini Index](https://data.census.gov/table?q=B19083)

---

## 📈 Dashboard

You can explore the interactive dashboard on **Tableau Public**:  
🔗 [Insert Tableau Public Link](https://bit.ly/DVFinalProjectGD)

---

## 💻 Code Repository

All data scripts and outputs are available in the `/code/` folder.  
🔗 [Insert GitHub Repository Link](https://bit.ly/DVFinalProjectGD-GitHub)

---

## 🙏 Acknowledgments

Huge thanks to **Professor Han Reichgelt** for the encouragement, guidance, and feedback throughout the course and project.

---

## 🤝 Let’s Connect

If you’re passionate about using data for social insights, public policy, or storytelling, feel free to connect through LinkedIn.

---

## 📌 License

This project is for academic and educational use. Please credit original data sources when reusing any content or dataset from this repository.

---


