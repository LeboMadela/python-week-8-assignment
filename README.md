# python-week-8-assignment
# 🦠 COVID-19 Global Data Tracker

This project analyzes real-world COVID-19 data from the [Our World in Data](https://www.kaggle.com/datasets/sandhyakrishnan02/latest-covid-19-dataset-worldwide) dataset. It explores global trends in cases, deaths, and vaccinations across countries over time. The project involves data cleaning, exploratory data analysis (EDA), and various visualizations using Python libraries such as pandas, matplotlib, and seaborn.

---

## 📌 Project Objectives

- Import and clean COVID-19 global data
- Analyze time trends in cases, deaths, and vaccinations
- Compare metrics across selected countries and regions
- Visualize trends using line charts, bar plots, histograms, and scatter plots
- Summarize insights in a structured and readable format

---

## 🗃️ Dataset

- Source: [Our World in Data - COVID-19](https://www.kaggle.com/datasets/sandhyakrishnan02/latest-covid-19-dataset-worldwide)
- File: `owid-covid-data.csv`
- Key columns used:
  - `date`
  - `location`
  - `continent`
  - `total_cases`
  - `new_cases`
  - `total_deaths`
  - `new_deaths`
  - `total_vaccinations`
  - `people_vaccinated`
  - `people_fully_vaccinated`

---

## 🛠️ Tools Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook (Anaconda environment)

---

## 📊 Visualizations

- **Line Chart**: Total COVID-19 cases over time for selected countries (`USA`, `India`, `South Africa`)
- **Bar Chart**: Top 10 countries by total cases on the latest recorded date
- **Histogram**: Distribution of total deaths globally
- **Scatter Plot**: Total vaccinations vs. total cases by country

---

## 🧹 Data Cleaning Steps

- Dropped rows with missing `date` or `location`
- Converted `date` column to datetime format
- Filled missing numeric values with `0` to ensure clean visualizations

---

## 📈 Key Findings

- The USA consistently leads in cumulative cases.
- Vaccination numbers show correlation with case trends in many countries.
- Distributions of total deaths highlight a skew toward a few severely impacted countries.

---

## ▶️ How to Run This Project

1. Clone the repository:
   git clone https://github.com/LeboMadela/python-week-8-assignment.git

2. Place owid-covid-data.csv in the working directory.

3. Open covid_analysis.ipynb or run the .py file in Jupyter or VS Code.

4. Run all cells to view the outputs and graphs.

# 📄 File Structure
- owid-covid-data.csv — dataset
- covid_analysis.ipynb — Jupyter Notebook with code and outputs
- README.md — this file

# 📜 License
This project is open-source and available under the MIT License

# 🙋‍♀️ Author
Moleboheng Madela

For questions or collaboration, feel free to reach out!
   

