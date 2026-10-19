# 🚦 Road Safety in Milan — Data Visualization Project

### An Analysis of Road Accidents, Severity, and Territorial Risk (2001–2024)

## 📌 Project Overview

**Road Safety in Milan** is a data visualization project that explores the evolution of road accidents in Milan, Italy, between 2001 and 2024.

Using publicly available datasets from the **Municipality of Milan Open Data Portal**, the project investigates long-term accident trends, injury severity, vehicle involvement, and geographical differences across Milan's municipalities.

The main objective is to transform complex road safety datasets into clear, meaningful, and interactive visualizations, making it easier to understand how road safety has evolved over time and identify areas with higher accident concentrations.

The project includes an **interactive web dashboard**, developed using HTML, CSS, and JavaScript, alongside statistical analyses and visualizations created with Python.

## 🎯 Project Objectives

The analysis focuses on five research questions:

1. How has road safety changed in Milan between 2001 and 2024?
2. How have the numbers of accidents, injured people, and deaths evolved over time?
3. Do these indicators follow similar trends, or do they reveal different patterns?
4. Which Milan municipalities show the highest accident rates relative to their resident populations?
5. What are the main limitations of police-recorded accident data?

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing and statistical analysis |
| Pandas | Data cleaning, transformation, and aggregation |
| Matplotlib | Statistical charts and visualizations |
| HTML5 | Dashboard structure |
| CSS3 | Dashboard layout and styling |
| JavaScript | Interactive visualizations and data aggregation |
| SVG | Dynamic graphical elements |
| GitHub Pages | Dashboard hosting and deployment |

## 📊 Dataset

The project uses official open datasets provided by the **Municipality of Milan**.

**Data sources:**

- Road accidents involving injuries, categorized by month and number of vehicles involved (2001–2024).
- Road accidents involving injuries, categorized by month and municipality or former decentralization zone (2001–2024).
- Resident population by citizenship and municipality (1999–2025).

The datasets are available in machine-readable formats, including CSV and JSON.

**Official source:** [Municipality of Milan Open Data Portal](https://dati.comune.milano.it/)

## 🔬 Methodology

The analysis follows a structured data visualization workflow.

### 1. Data Collection

The relevant datasets were identified and downloaded from the official Municipality of Milan Open Data Portal.

### 2. Data Cleaning and Processing

Python and Pandas were used to prepare the datasets.

The preprocessing included:

- Checking column names and numerical formats.
- Identifying missing or inconsistent values.
- Verifying year and month consistency.
- Standardizing municipality identifiers.
- Aggregating monthly observations into annual summaries.

### 3. Data Transformation

Several indicators were calculated to support the analysis:

**Injured People**

Calculated by combining recorded injuries and deaths.

**Accident Severity**

Measured as the number of injured people per accident.

**Accidents per 10,000 Residents**

Used to compare municipalities with different population sizes.

```text
Accident Rate =
(Number of Accidents / Resident Population) × 10,000
```

### 4. Data Analysis

The analysis applies descriptive statistics, trend analysis, year-over-year comparisons, and normalized indicators to identify patterns in road safety.

### 5. Data Visualization

Static charts were developed using Matplotlib, while the interactive dashboard was implemented with HTML, CSS, JavaScript, and SVG.

## 💻 Interactive Dashboard

The project includes an interactive dashboard designed to make road safety data accessible and easy to explore.

### Main Features

- **Annual Trends:** Explore changes in road accidents over time.
- **Monthly Patterns:** Investigate variations across different months.
- **Accident Severity:** Compare accidents, injuries, and fatalities.
- **Vehicle Involvement:** Analyze accidents by the number of vehicles involved.
- **Municipality Rankings:** Compare geographical areas using population-normalized indicators.
- **Interactive Exploration:** Explore different dimensions of road safety through dynamic visualizations.

The dashboard runs directly in a web browser and does not require a backend server.

### Running the Dashboard Locally

1. Clone or download this repository.
2. Locate the HTML dashboard file.
3. Open the file in a modern web browser.
4. Explore the interactive charts and indicators.

The dashboard is also designed for deployment through **GitHub Pages**.

## 📈 Key Findings

### 1. Long-Term Road Safety Improvement

Between 2001 and 2024, Milan experienced a substantial decrease in recorded road accidents, injuries, and fatalities.

| Indicator | 2001 | 2024 | Change |
|---|---:|---:|---:|
| Road Accidents | 54,071 | 30,068 | -44.4% |
| Injured People | 75,851 | 38,969 | -48.6% |
| Deaths | 1,073 | 383 | -64.3% |

These findings indicate a general improvement in road safety, particularly regarding fatal outcomes.

### 2. Different Trends in Accident Severity

Although accidents, injured people, and deaths generally follow a downward trend, the magnitude of their reductions differs.

Fatalities experienced the strongest decline, suggesting that improvements in road safety are not limited to accident frequency.

### 3. Impact of the COVID-19 Pandemic

A particularly sharp decrease in accidents is visible around 2020.

This reduction was likely influenced by mobility restrictions and reduced traffic volumes during the COVID-19 pandemic.

After 2020, the indicators partially increased again, highlighting the importance of distinguishing temporary changes from long-term trends.

### 4. Geographical Differences

The municipality-level analysis reveals differences in accident rates across Milan.

In 2024, **Municipio 9 — Porta Garibaldi / Niguarda** recorded the highest normalized accident rate relative to its resident population.

However, this indicator should not be interpreted as a complete measure of road exposure, since residents are not the only people using the local road network.

## ⚠️ Data Limitations

Several limitations must be considered when interpreting the results:

- Only police-recorded accidents involving injuries or fatalities are included.
- Minor or unreported accidents may be missing.
- Fatalities are counted when death occurs within 30 days of the accident.
- Some accident records may contain missing municipality information.
- Resident population does not fully represent daily road traffic exposure.
- Commuters, tourists, students, and delivery workers may influence accident statistics without being included in the resident population.

Consequently, population-normalized accident rates should be interpreted as comparative indicators rather than definitive measures of individual accident risk.

## 🚀 Future Improvements

Possible future developments include:

- Integrating more recent accident datasets.
- Adding geographical maps and interactive spatial visualizations.
- Including traffic volume and mobility data to improve risk estimates.
- Investigating relationships between road accidents, infrastructure, and urban mobility.
- Developing predictive models to identify potential accident patterns.

## 📚 References

The datasets used in this project were obtained from the Municipality of Milan Open Data Portal.

[Municipality of Milan — Open Data](https://dati.comune.milano.it/)

## 📄 License

The project presentation is shared under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license.

For further information:

[Creative Commons License](https://creativecommons.org/licenses/by-sa/4.0/)

## 👨‍💻 Author

**Biagio Chiarandà**

University of Milano-Bicocca

**Project:** Data Visualization — Road Safety in Milan

---

*This project demonstrates how open data, statistical analysis, and interactive visualization can help communicate urban road safety trends and support a better understanding of mobility-related challenges.*
