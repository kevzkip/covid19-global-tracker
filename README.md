# 🌍 COVID-19 Global Data Tracker Analysis

This project analyzes and visualizes global COVID-19 trends using real-world data. It tracks the spread of the virus, death rates, vaccination progress, and key insights from countries across the world.

## 📚 Project Overview

This analysis uses data from [Our World in Data](https://ourworldindata.org/covid-cases) to explore COVID-19's impact on different countries. The project covers:

- Case growth trends across selected countries
- Death rates and vaccinations progress over time
- Comparative analysis between countries on critical health metrics

Key metrics analyzed:
- Total cases and deaths
- Death rate (deaths / total cases)
- Vaccination progress
- Cases per million population

## 🔧 Tools & Libraries Used

- **Python**: Core programming language
- **Jupyter Notebook**: For interactive coding and analysis
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib & Seaborn**: Data visualization (charts and graphs)
- **Plotly**: Interactive visualizations (maps)

## 📁 Files Included

- **`covid_analysis.ipynb`**: Jupyter Notebook containing the entire analysis and visualizations.
- **`owid-covid-data.csv`**: [Download](https://covid.ourworldindata.org/data/owid-covid-data.csv) The raw dataset from *Our World in Data*, used for the analysis.

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/kevzkip/covid19-global-tracker.git
   cd covid19-global-tracker
   ```
2. Ensure you have all dependencies installed. You can install them using pip:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Open the Jupyter Notebook (covid_analysis.ipynb) in Jupyter or VS Code and run the cells sequentially.

4. Ensure that the owid-covid-data.csv file is in the same directory as the notebook, or update the path in the code if you place it elsewhere.

5. Run the notebook to generate the visualizations and analysis.

   Note: This analysis uses data up to the most recent date available in the [owid-covid-data.csv](https://covid.ourworldindata.org/data/owid-covid-data.csv).

## 🔍 Insights and Key Findings

- **Case Growth**: The United States exhibited the steepest rise in cases, while developing countries like Kenya showed more gradual growth.
- **Vaccination Rollout**: Wealthier countries such as the US and the UK had a rapid vaccination rollout, whereas developing countries faced challenges in vaccine access.
- **Death Rates**: Brazil had the highest death rate among the selected countries, while Germany exhibited a significantly lower death rate, likely due to better healthcare infrastructure.
- **Global Case Distribution**: Different regions exhibited varying levels of infection density, highlighting the importance of localized health measures.

## 📊 Visualizations and Analysis

The project includes several visualizations that highlight key aspects of the COVID-19 pandemic:

- **Case Progression Over Time**: Tracks the rise in total cases across countries.
- **Comparative Analysis**: Compares countries on total cases, death rates, vaccination rates, and cases per million population.
- **Global Distribution**: A choropleth map displaying global cases per million population.

## 🔄 Data Source

The data used in this analysis is sourced from **Our World in Data**, a comprehensive resource for global COVID-19 statistics. The dataset includes daily updates on total cases, deaths, vaccinations, and other important metrics across various countries.

## 📋 License

This project is open-source and available under the MIT License. You are free to use, modify, and distribute this code as needed. Attribution is appreciated.

## 👨‍💻 Author

Developed by **Kevin Kipkorir**.
