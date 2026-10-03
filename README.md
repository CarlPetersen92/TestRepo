# IBM Data Analyst Capstone Project

## 📌 Project Overview
This repository contains the comprehensive portfolio developed for the IBM Data Analyst Professional Certificate Capstone Project. The objective of this project is to analyze the tech job market landscape by collecting data from multiple web platforms, processing and cleaning the datasets, constructing an interactive analytics dashboard, and delivering data-driven career market insights.

## 📊 Core Data Workflow & Milestones
*   **Data Collection & Sourcing:** Harvested live technological listings programmatically using REST APIs and automated web scraping techniques.
*   **Data Wrangling & Processing:** Cleaned large-scale survey response tables, resolved formatting schema mismatches, dropped duplicate records, and handled missing outliers.
*   **Exploratory Data Analysis (EDA):** Determined overall market distribution metrics using descriptive statistical tools.
*   **Interactive Dashboard Design:** Built dynamic analytical visual components using Plotly and Dash to view metrics on the fly.

## 🛠️ Technology Stack & Tools
*   **Programming Language:** Python (Libraries: `requests`, `pandas`, `beautifulsoup4`, `matplotlib`, `seaborn`)
*   **Development Platform:** Jupyter Notebook / Skills Network Labs
*   **Analytics Visualization Engine:** Plotly Dash / IBM Cognos
*   **Database Infrastructure:** SQL / IBM Db2 on Cloud

## 🚀 Repository Structure
├── data/
│   ├── job-postings.csv        # Programmatic API harvested raw text dataset
│   └── survey-responses.csv    # Consolidated workforce survey data
├── notebooks/
│   ├── 1_Data_Collection.ipynb # REST API extraction and web scraping code
│   └── 2_Data_Wrangling.ipynb  # Data cleaning and normalization rules
├── dashboard/
│   └── app.py                  # Plotly Dash application build script
└── README.md
