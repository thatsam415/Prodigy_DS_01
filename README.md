# 🌍 World Population Data Visualization (2001–2022)

## 📌 Project Overview

This project presents a comprehensive analysis and visualization of world population data from 2001 to 2022. Using Python, pandas, seaborn, and matplotlib, we explore patterns and trends in total, male, and female populations across different countries. We also identify top and bottom countries by population for various years.

## 📁 Dataset Details

The dataset contains yearly population statistics for multiple countries, including:

| Series Code | Description |
|-------------|-------------|
| SP.POP.TOTL | Total population |
| SP.POP.TOTL.MA.IN | Male population (absolute) |
| SP.POP.TOTL.FE.IN | Female population (absolute) |
| SP.POP.TOTL.MA.ZS | Male population (% of total) |
| SP.POP.TOTL.FE.ZS | Female population (% of total) |

### 🧮 Columns

- **Country Name**
- **Series Code**
- **Population values from 2001 to 2022**

## 🔧 Tools & Libraries Used

- Python 🐍
- Jupyter Notebook 📒
- pandas
- numpy
- seaborn
- matplotlib

## 📊 Key Visualizations

- Bar plots of **Top 10** and **Bottom 10** countries by total population (2001, 2010, 2016, 2022)
- Gender-based bar plots for **Top 10** and **Bottom 10** countries by male and female population (2022)
- **Stacked bar charts** showing male and female population composition for top and bottom countries

## 🚀 Features

- Clean and preprocess data (remove duplicates, check nulls)
- Extract and compare population data over multiple years
- Highlight global population distribution patterns using visual plots

## 📂 File Structure

```plaintext
├── worldpopulationdata.csv
├── World_Population_Dataset_Analysis.ipynb
```
## 🧠 Insights & Conclusion
 - Countries like India and China consistently top the population charts.
 - Smaller island nations and microstates form the bottom 10 in population.
 - Gender distribution remains relatively balanced in most countries.
