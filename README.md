Seasonal Agriculture Performance Analysis

Major Project | VOIS AICTE Program

A data analysis and visualization project studying agricultural performance across Kharif, Rabi, and Zaid seasons, with focus on crop yield, profitability, irrigation efficiency, rainfall relationships, risk, and regional performance.

Project Overview

Agricultural performance can vary across seasons because of environmental conditions, farming practices, resource availability, and market-related factors. This project analyzes the provided agricultural dataset to identify meaningful patterns, trends, relationships, and variations.

Workflow: Data → Cleaning → Feature Engineering → Exploratory Analysis → Visualization → Statistical Testing → Insights

Dataset

Records: 4,000

Variables: 28

Seasons: Kharif, Rabi, Zaid

Format: CSV / Excel

Analysis Areas

Seasonal Performance — Compare yield and profit across Kharif, Rabi, and Zaid.

Crop Performance — Compare crop profitability and crop yield across seasons.

Irrigation Efficiency — Evaluate irrigation methods using yield, water use, and water efficiency.

Environmental Relationships — Study rainfall, yield, water efficiency, and profit relationships.

Regional Performance — Compare average agricultural profit across states.

Statistical Analysis — Use the Kruskal–Wallis test to examine seasonal yield differences.

Feature Engineering

The analysis derives:

Profit Margin (%)

Cost per Hectare (INR)

Revenue per Hectare (INR)

Profit per Hectare (INR)

Key Findings

Kharif had the highest average yield at approximately 5.63 t/ha.

Kharif had the highest average profit at approximately ₹178,915.

Zaid had a negative average profit of approximately ₹24,805.

Drip irrigation recorded the highest average yield at approximately 6.58 t/ha.

Rainfed farming recorded the highest average water-efficiency value at approximately 7.56 t per 1,000 m³.

Yield and water efficiency showed a strong positive correlation (r ≈ 0.91).

Yield and profit showed a moderate positive correlation (r ≈ 0.49).

Rainfall and yield showed very little linear correlation in this dataset (r ≈ 0.03).

Sugarcane and Chilli recorded the highest average profits among the analyzed crops.

The Kruskal–Wallis test indicated a statistically significant difference among seasonal yield distributions (H = 68.713, p ≈ 1.20 × 10⁻¹⁵).

Correlation describes relationships observed in the dataset; it does not establish causation.

Technologies Used

Python

Pandas

NumPy

Matplotlib

SciPy

Jupyter Notebook / Google Colab

Microsoft Excel

GitHub

Project Structure

Seasonal-Agriculture-Performance-Analysis/
│
├── README.md
├── Dataset/
├── Analysis/
├── Results/
└── Presentation/

How to Run

Clone or download the repository.

Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.

Keep the dataset in the data/ folder.

Run the notebook cells sequentially.

The notebook performs cleaning, feature engineering, analysis, visualization, and statistical testing.

Outputs

The project includes visualizations for:

Seasonal yield and profit

Crop profitability

Crop-by-season yield

Irrigation performance and water efficiency

Rainfall versus yield

Correlation analysis

State-wise profit

Profit and yield distributions

Outlier analysis

Future Scope

Potential extensions include:

Multi-year agricultural datasets

Weather and climate forecasts

Market price and demand data

Soil and crop-health information

Predictive yield and profit models

Machine-learning-based crop recommendations

Interactive dashboards for agricultural decision-making

Project Deliverables

Executed data-analysis notebook

Agricultural dataset

Data visualizations

Major project presentation

Project documentation

