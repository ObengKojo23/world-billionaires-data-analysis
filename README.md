# 💰💵 **World’s Billionaires Data Analysis** 💵💰

### 🛠 Technologies Used

- **Python**: Data manipulation and analysis
- **Pandas**: For data manipulation
- **Matplotlib & Seaborn**: For data visualization
- **Plotly**: For interactive visualizations
- **Scipy**: For statistical analysis
- **Jupyter Notebook**: For organizing the analysis

---
### 🌍 Introduction

This analysis explores various aspects of the global billionaire population using a dataset of billionaires, including their demographic details, wealth, and geographical distribution. The focus is on understanding how factors such as gender, age, region, and wealth type correlate with the concentration of billionaires worldwide. Additional insights include trends in self-made versus inherited wealth, birth month distributions, and the relationship between economic indicators and the number of billionaires in a country.

---

### 💾 Dataset Summary

| Column                             | Description                                                   |
|------------------------------------|---------------------------------------------------------------|
| `rank`                             | The ranking of the billionaire in terms of wealth.             |
| `finalWorth`                       | The final net worth of the billionaire in U.S. dollars.        |
| `category`                         | The category or industry in which the billionaire's business operates. |
| `personName`                       | The full name of the billionaire.                             |
| `age`                              | The age of the billionaire.                                   |
| `country`                          | The country where the billionaire resides.                    |
| `city`                             | The city where the billionaire resides.                       |
| `source`                           | The source of the billionaire's wealth.                       |
| `industries`                       | The industries associated with the billionaire's business interests. |
| `countryOfCitizenship`             | The country of citizenship of the billionaire.                |
| `organization`                     | The name of the organization or company associated with the billionaire. |
| `selfMade`                         | Indicates whether the billionaire is self-made (True/False).  |
| `status`                           | "D" for self-made (Founders/Entrepreneurs) and "U" for inherited wealth. |
| `gender`                           | The gender of the billionaire.                                |
| `birthDate`                        | The birthdate of the billionaire.                             |
| `birthYear`, `birthMonth`, `birthDay` | Details about the birth year, month, and day of the billionaire. |
| `cpi_country`, `gdp_country`       | Economic indicators like CPI and GDP for the billionaire's country. |
| `population_country`               | Population of the billionaire's country.                      |
| ...                                | Additional socioeconomic factors tied to the billionaire's country. |

---

### 📋 Table of Contents

1. [Importing Packages](#one)
2. [Loading Data](#two)
3. [Exploratory Data Analysis (EDA) - Non-Graphical](#three)
4. [Data Preprocessing](#four)
5. [Exploratory Data Analysis (EDA) - Graphical](#five)
6. [Summary](#six)

---

### 🚀 How to Run This Project

1. **Clone the Repository**  
   Run the following command to clone the repository to your local machine:
   ```bash
   git clone https://github.com/ObengKojo23/worlds-billionaires-analysis.git
2. **Install Dependencies**  
   Install the required Python packages by running:
   ```bash
   pip install -r requirements.txt
3. **Run the Jupyter Notebook**  
   Start Jupyter Notebook and run the `billionaires-data-analysis-2023.ipynb` file to reproduce the analysis. Use the following command to launch Jupyter:

   ```bash
   jupyter notebook
---

### 🔍 Exploratory Data Analysis

The following 17 questions were addressed using the dataset:

1. **What is the distribution of billionaires by gender?**
2. **How is wealth distributed among self-made billionaires compared to those who inherited their wealth?**
3. **Which countries and cities have the highest concentration of billionaires?**
4. **What is the age distribution of billionaires?**
5. **Which industries do most billionaires belong to?**
6. **What are the most common sources of wealth for billionaires?**
7. **How is the net worth of billionaires distributed globally?**
8. **What percentage of billionaires are self-made versus inherited?**
9. **How does the billionaire population correlate with economic indicators such as GDP and CPI?**
10. **Is there a relationship between population size and the number of billionaires in a country?**
11. **How does the age of billionaires correlate with their net worth?**
12. **Which countries have the highest number of self-made billionaires?**
13. **What is the distribution of billionaires by birth month?**
14. **Is there a noticeable difference in the number of billionaires by gender in different industries?**
15. **Which organizations or companies are most frequently associated with billionaires?**
16. **What trends can be observed in the wealth accumulation of younger versus older billionaires?**
17. **How has the number of billionaires evolved over time, particularly in key industries?**

---

- **Non-Graphical Analysis**: The first step of the EDA involves looking at summary statistics, null values, and unique values for various columns to get an understanding of the data structure and potential cleaning needs.
  
- **Graphical Analysis**: Visuals such as bar plots, pie charts, and histograms are used to uncover trends in billionaire distribution by gender, age, wealth source, and geographical region.

---

### 🧑‍💻 Key Insights

- **Wealth Distribution**: Analysis of net worth reveals significant disparities between self-made and inherited billionaires.
- **Geographic Focus**: Certain countries and cities are home to a disproportionately large number of billionaires, providing insights into global wealth concentration.
- **Demographics**: Trends in gender and age distribution show that most billionaires fall within specific age brackets, and self-made wealth is more common among younger billionaires.

---

### 📊 Summary

The analysis provides a comprehensive look at the world's billionaire population and the various factors influencing wealth creation and distribution. By correlating socioeconomic factors with billionaire presence, this project sheds light on how wealth is amassed and maintained globally.

---
