#  New York Crime Data Analysis & Interactive Dashboard

Author: Yash  
Project Type: Academic / Portfolio Project  

---

## Project Overview
This project implements an end-to-end data analytics workflow for analyzing New York City crime data.  
It includes data cleaning, transformation, optimization using Parquet format, and visualization through an interactive Plotly Dash dashboard.

The project demonstrates practical experience in data analysis, data engineering fundamentals, and dashboard deployment using Python and Docker.

---

## Objectives
- Clean and preprocess raw crime data  
- Convert CSV data into optimized Parquet format  
- Build a structured backend data pipeline  
- Develop an interactive Plotly Dash dashboard  
- Containerize the application using Docker  

---

## Key Highlights
- Efficient data storage using columnar Parquet files  
- Transition from Jupyter notebooks to Python scripts  
- Interactive visualizations with Plotly Dash  
- Dockerized setup for reproducible execution  
- End-to-end data workflow from raw data to dashboard  

---

## Tech Stack
- Python  
- Pandas  
- NumPy  
- PyArrow (Parquet)  
- Plotly & Dash  
- Jupyter Notebook  
- Docker & Docker Compose  

---

## Project Structure
```text
Data-Analysis-parquet-dashboard/
├── backend/
│   ├── backend.py
│   ├── backend.ipynb
│   └── requirements.txt
├── frontend/
│   └── dashboard.py
├── data/
│   ├── raw/
│   └── processed/
├── cleaning.ipynb
├── yearly_conversion_Parquet.ipynb
├── Dockerfile
├── docker-compose.yml
├── .gitignore
└── README.md
```
## Data Workflow

- Raw CSV files are stored in the data/raw/ directory
- Data cleaning and preprocessing are performed using Jupyter notebooks
- Cleaned data is converted into Parquet format and stored in the data/processed/ directory
- Backend scripts load and aggregate the processed data
- The Dash application visualizes the processed data interactively

## Dashboard Features

- Filtering by year, borough, crime type, demographics, and age group
- Interactive bar charts and trend visualizations
- Optimized data loading using Parquet files

## How to Run the Project

Prerequisites
- Python 3.9 or higher
- Docker
- Docker Compose

  ### Run Locally 
  ```
   pip install -r backend/requirements.txt
  python frontend/dashboard.py
  ```
  Open in browser
  ```
  http://localhost:8050
  ```
  ### Run Using Docker
  ```
  docker-compose up --build
  ```
  Open in browser
  ```
  http://localhost:8050
  ```

## Future Improvements
- Add machine learning models for prediction
- Improve schema validation and error handling
- Deploy the dashboard to cloud platforms (Render / AWS)
- Automate data ingestion and refresh pipelines
- Enhance dashboard UI and performance
  


  
