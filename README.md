# Data Visualisation Analysis

A data visualisation project combining a Power BI dashboard analysing UK road traffic accident data with a Python/Jupyter exploratory analysis of retail sales data.

## Project Overview

This repository contains two linked visualisation tasks:

### Task 1 — UK Road Safety Data (Power BI)
An analytical dashboard exploring the location, frequency, and causes of road traffic accidents across the United Kingdom, aimed at local government leaders, traffic management departments, and road safety experts.

**Key features explored:**
- Severity of collisions (fatal, serious, slight)
- Time band distribution (morning, afternoon, evening, night)
- Weather conditions and their effect on accident severity
- Road speed limits and road surface conditions

**Key insights:**
- Higher accident concentration in major cities (London, Manchester, Birmingham), likely due to traffic volume
- Most accidents occur in clear weather, suggesting human behaviour plays a large role
- Afternoon periods see the highest frequency of collisions
- Single carriageway roads contribute the most to accident frequency

### Task 2 — Sample Superstore Analysis (Python/Jupyter)
An exploratory data analysis of the Sample Superstore dataset (Kaggle), examining sales, profit, discount, and shipping trends.

**Visuals produced:**
- Category and sub-category sales/profit breakdowns
- Monthly sales trend
- Discount vs. profit scatter plot
- Region vs. category heatmap
- Shipping analysis

## Repository Structure

```
├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
├── results-section.md
├── Task_1_report.pdf
├── Task1_PowerBI.pbix
├── Task2_data.csv
└── Task2_jupyter.ipynb
```

## How to Run

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Place `Task2_data.csv` in the same directory as `Task2_jupyter.ipynb`
4. Open the notebook: `jupyter notebook Task2_jupyter.ipynb`
5. Run all cells: **Kernel > Restart & Run All**
6. Open `Task1_PowerBI.pbix` in Power BI Desktop to view the dashboard

## Tools Used

- **Power BI** — interactive dashboard and geographic visualisation
- **Python** (pandas, numpy, matplotlib, seaborn, plotly) — data cleaning and exploratory analysis
- **Jupyter Notebook** — analysis environment

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
