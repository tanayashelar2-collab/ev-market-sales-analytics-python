

# EV Market & Sales Analytics Using Python

## Project Overview

This project analyzes 3,022 electric vehicle records to understand 2024 recorded sales performance, manufacturer and model performance, vehicle specifications, charging technologies, and manufacturing patterns.

The project uses Python-based exploratory data analysis to identify patterns and relationships that can support business decision-making.

## Business Problem

EV companies need data-driven insights to understand product performance and market patterns. This project analyzes EV data to explore sales performance, vehicle characteristics, battery and charging technologies, and manufacturing distribution.

## Objectives

- Analyze manufacturer and model sales performance
- Identify top-performing EV models
- Explore price and range relationships with sales
- Analyze battery and charging technologies
- Analyze manufacturing countries
- Explore safety and autonomous driving features
- Identify relationships between numerical EV features

## Dataset

- **Records:** 3,022
- **Columns:** 17
- **Main Sales Metric:** Units_Sold_2024
- **Vehicle Years:** 2015–2025

### Main Features

- Manufacturer
- Model
- Year
- Battery Type
- Battery Capacity
- Range
- Charging Type
- Charge Time
- Price
- Country of Manufacture
- Autonomous Level
- Safety Rating
- Units Sold in 2024
- Warranty Years

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Analysis

The project includes:

1. Data Cleaning
2. Missing Value Treatment
3. Duplicate Detection
4. Manufacturer Sales Analysis
5. EV Model Sales Analysis
6. Price vs Sales Analysis
7. Range vs Sales Analysis
8. Battery & Charging Technology Analysis
9. Country Analysis
10. Safety & Autonomous Feature Analysis
11. Correlation Analysis
12. Business Insights

## Key Findings

- Ferrari recorded the highest total 2024 units sold among manufacturers in the dataset.
- Rimac Nevera recorded the highest units sold among the analyzed EV models.
- Price vs Sales correlation was **-0.013**.
- Range vs Sales correlation was **0.014**.
- The dataset contains multiple battery and charging technologies.

## Data Limitation

The analysis is based on the provided dataset and its recorded `Units_Sold_2024` values. These figures should not automatically be interpreted as verified real-world market sales.

Correlation results describe relationships within this dataset and do not establish causation.

## Project Structure

```text
EV-Market-Sales-Analytics/
│
├── data/
│   └── ev_data.csv
│
├── notebook/
│   └── EV_Market_Sales_Analysis.ipynb
│
├── visualizations/
│
├── business_insights.md
│
├── README.md
│
└── requirements.txt
