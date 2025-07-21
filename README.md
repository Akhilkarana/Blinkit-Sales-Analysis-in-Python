# Blinkit Sales Performance Analysis
This repository contains a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution. The objective of this project is to identify key insights and opportunities for optimization using various Key Performance Indicators (KPIs) and data visualizations.

## Table of Contents

  - [Project Overview](https://www.google.com/search?q=%23project-overview)
  - [Business Requirements](https://www.google.com/search?q=%23business-requirements)
      - [KPIs](https://www.google.com/search?q=%23kpis)
      - [Chart Requirements](https://www.google.com/search?q=%23chart-requirements)
  - [Dataset](https://www.google.com/search?q=%23dataset)
  - [Analysis and Visualizations](https://www.google.com/search?q=%23analysis-and-visualizations)
  - [How to Use](https://www.google.com/search?q=%23how-to-use)
  - [Technologies Used](https://www.google.com/search?q=%23technologies-used)
  - [Files in this Repository](https://www.google.com/search?q=%23files-in-this-repository)

## Project Overview

This project aims to provide a deep dive into Blinkit's operational data to understand factors influencing sales, customer ratings, and item distribution. By analyzing various dimensions such as item fat content, item type, outlet characteristics, and location, we seek to uncover actionable insights for business improvement.

## Business Requirements

The analysis was guided by specific business requirements and a set of defined KPIs and visualization needs.

### KPIs

The following Key Performance Indicators were used for the analysis:

  * **Total Sales:** The overall revenue generated from all items sold.
  * **Average Sales:** The average revenue per sale.
  * **Number of Items:** The total count of different items sold.
  * **Average Rating:** The average customer rating for items sold.

### Chart Requirements

The analysis required the creation of specific visualizations to address different business questions:

1.  **Total Sales by Fat Content:**

      * **Objective:** Analyze the impact of fat content on total sales.
      * **Additional KPI Metrics:** Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
      * **Chart Type:** Donut Chart.

2.  **Total Sales by Item Type:**

      * **Objective:** Identify the performance of different item types in terms of total sales.
      * **Additional KPI Metrics:** Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
      * **Chart Type:** Bar Chart.

3.  **Fat Content by Outlet for Total Sales:**

      * **Objective:** Compare total sales across different outlets segmented by fat content.
      * **Additional KPI Metrics:** Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
      * **Chart Type:** Stacked Column Chart.

4.  **Total Sales by Outlet Establishment:**

      * **Objective:** Evaluate how the age or type of outlet establishment influences total sales.
      * **Chart Type:** Line Chart.

5.  **Sales by Outlet Size:**

      * **Objective:** Analyze the correlation between outlet size and total sales.
      * **Chart Type:** Donut/Pie Chart.

6.  **Sales by Outlet Location:**

      * **Objective:** Assess the geographic distribution of sales across different locations.
      * **Chart Type:** Funnel Map.

## Dataset

The analysis utilizes the `blinkit_data.csv` file, which contains various attributes related to items, outlets, and sales performance.
The dataset includes columns such as:

  * `Item Fat Content`
  * `Item Identifier`
  * `Item Type`
  * `Outlet Establishment Year`
  * `Outlet Identifier`
  * `Outlet Location Type`
  * `Outlet Size`
  * `Outlet Type`
  * `Item Visibility`
  * `Item Weight`
  * `Sales`
  * `Rating`

## Analysis and Visualizations

The `Blinkit Analysis in Python.ipynb` Jupyter notebook contains the Python code used for data loading, cleaning, analysis, and visualization. The `Blinkit Analysis.pptx` presentation provides a summary of the business requirements and the key charts generated as part of this analysis.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/Blinkit-Sales-Analysis.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Blinkit-Sales-Analysis
    ```
3.  **Install the required libraries** (if you don't have them already):
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```
4.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook "Blinkit Analysis in Python.ipynb"
    ```
5.  Run the cells in the notebook to reproduce the analysis and visualizations.

## Technologies Used

  * **Python**
  * **Pandas** (for data manipulation)
  * **NumPy** (for numerical operations)
  * **Matplotlib** (for basic plotting)
  * **Seaborn** (for enhanced statistical visualizations)
  * **Jupyter Notebook** (for interactive analysis)
  * **Microsoft PowerPoint** (for the presentation)

## Files in this Repository

  * `Blinkit Analysis in Python.ipynb`: The Jupyter Notebook containing the Python code for data analysis and visualization.
  * `blinkit_data.csv`: The raw dataset used for the analysis.
  * `Blinkit Analysis.pptx`: A PowerPoint presentation outlining the business requirements and chart specifications.
  * `blinkit_logo.png`: The Blinkit logo used in this README.

-----
