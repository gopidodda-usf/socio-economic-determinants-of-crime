# 📊 Socio-Economic Determinants of Crime

Crime is a multifaceted societal issue influenced not just by poverty but by broader socio-economic variables like **income levels**, **inequality**, and **unemployment**. This project seeks to uncover meaningful patterns between these variables and crime, and to identify whether there exists a threshold beyond which economic improvement leads to a measurable decline in criminal activity.

Spanning data from **2010 to 2023**, this study analyzes crime trends across U.S. states using **state-level datasets** and presents the findings through **interactive visual storytelling**.

---

### 🧠 Project Overview

The project focuses on analyzing how the following indicators affect crime rates:

- Family Income
- Income Inequality (Gini Index)
- Unemployment Rate
- Poverty Levels

Data was collected from official **U.S. Census** and **FBI** sources using **Python**, cleaned and structured into Excel files, and visualized using **Tableau**. This end-to-end process enabled rich, interactive storytelling across both time and geography.

---

### 🎯 Research Questions & Findings

1. **Is there a specific income threshold beyond which crime rates significantly decline?**

   ✅ Yes. A **$69,000 threshold** was identified, beyond which crime rates stabilize and remain consistently lower. This suggests a potential tipping point where economic well-being translates to public safety.

2. **How does income inequality impact different types of crimes (violent vs. property crimes)?**

   ⚠️ **Violent crimes** show a **steeper increase** with rising income inequality compared to property crimes, indicating that inequality has a stronger impact on more severe offenses.

3. **How do economic indicators such as unemployment rate and poverty affect crime rates?**

   📉 States with **lower poverty and unemployment** levels, especially after 2014, showed **significant drops in crime rates**, supporting the idea that economic recovery reduces crime.

---

### 📁 Repository Structure

```
├── code/
│   ├── Crime Data.ipynb                          # Extracts and processes crime data from FBI API
│   ├── Economic Data.ipynb                       # Pulls and cleans economic data from Census API
│   ├── Gini Data.ipynb                           # Fetches income inequality data from Census API
│   ├── crime_data_2010_2023.xlsx                 # Final crime dataset
│   ├── economic_characteristics_2010_2023.xlsx   # Final dataset with income, poverty, and unemployment metrics
│   └── gini_index_2010_2023.xlsx                 # Final dataset with Gini index data
├── Final-Project-GD.pdf                          # Full project report detailing methodology and insights
├── Final-Project-GD.twbx                         # Tableau packaged workbook with interactive dashboards
└── README.md                                     # You're here!
```

---

### 🛠️ Tools & Technologies

- **Python** – For data extraction and cleaning (FBI Crime Data API, Census Data API)
- **Jupyter Notebook** – To write and run all python scripts
- **Tableau** – For visual analytics and storytelling
- **Excel** – Clean data output for Tableau ingestion

---

### 🔗 Data Sources

The project uses publicly available data from trusted government sources:

- **Crime Statistics**:
  📎 [**FBI Crime Data Explorer API**](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/explorer/crime/query)

- **Economic Characteristics**:
  📎 [**U.S. Census Bureau - Economic Data**](https://data.census.gov/table?q=dp03)

- **Income Inequality (Gini Index)**:
  📎 [**U.S. Census Bureau - Gini Index**](https://data.census.gov/table?q=B19083)

---

### 📈 Dashboard

You can explore the interactive dashboard on [**Tableau Public**](https://bit.ly/DVFinalProjectGD).

---

### 💻 Code Repository

All data scripts and outputs are available in the `/code/` folder of this [**GitHub Repository**](https://bit.ly/DVFinalProjectGD-GitHub).

---

### 🙏 Acknowledgments

This project was developed as part of the ***Data Visualization*** course at the University of South Florida. Huge thanks to **Prof. Han Reichgelt** for the encouragement, guidance, and feedback throughout the course and project.

---

### 🤝 Let’s Connect

If diving into data to uncover social trends or spark meaningful conversations sounds like your thing, let’s connect on [**LinkedIn!**](https://www.linkedin.com/in/gopidodda96/)

---

### 📌 License

This project is for academic and educational use. Please credit original data sources when reusing any content or dataset from this repository.

---


