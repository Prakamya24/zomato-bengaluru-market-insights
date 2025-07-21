# Zomato Restaurant Market Insights — Bengaluru

## Project Overview
This project analyzes over 50,000 restaurants in Bengaluru using Zomato's publicly available dataset. The objective is to extract actionable insights related to restaurant ratings, pricing, cuisine preferences, and customer behavior patterns. The analysis supports data-driven decision-making for business strategies and marketing.

## Data Cleaning & Preparation
- Addressed missing values in critical features such as ratings, costs, and locations.
- Standardized and transformed categorical variables for consistency.
- Processed and cleaned textual data fields for analysis readiness.

## Exploratory Data Analysis (EDA)
- Visualized distributions and trends in restaurant locations, ratings, pricing, and cuisines.
- Assessed customer service preferences like online ordering and table booking.
- Identified key factors influencing customer retention and profitability.

## Customer Segmentation
- Employed K-Means clustering on key numerical and categorical features to segment restaurants.
- Profiled clusters to understand differentiating characteristics in terms of pricing, popularity, and service offerings.
- Generated insights to tailor targeted marketing and operational strategies.

## Project Structure
```plaintext
├── data/
│   ├── raw/                 # Original dataset files
│   └── cleaned/             # Cleaned and processed datasets
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_customer_segmentation.ipynb
├── visuals/                 # Visualizations and plots
├── README.md                # Project overview and documentation
├── requirements.txt         # Project dependencies
└── .gitignore               # Git ignore rules
```

## How to Run
1. Clone the repository to your local machine.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute notebooks in sequential order:
   - `01_data_cleaning.ipynb`
   - `02_exploratory_analysis.ipynb`
   - `03_customer_segmentation.ipynb`

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

(See `requirements.txt` for exact versions.)

## Author
**Prakamya Verma**  
prakamya0124@gmail.com
[Linkdin](https://www.linkedin.com/in/prakamya-verma/)
---

*This project is part of a data analysis portfolio showcasing advanced data cleaning, visualization, and clustering techniques applied to real-world restaurant data.*
