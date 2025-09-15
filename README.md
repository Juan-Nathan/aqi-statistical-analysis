# 🏭 Statistical Analysis of U.S. Air Quality Index Data

This project analyzes U.S. Air Quality Index (AQI) data collected by the Environmental Protection Agency (EPA) using **statistical inference methods** in Python to support data-driven decision-making. It is framed around two hypothetical organizations:

- **Ripple Renewable Energy**: Uses **confidence intervals** to determine which states might qualify for renewable energy subsidies under a new federal policy.  
- **Repair Our Air**: Uses **hypothesis testing** to guide environmental strategies, such as focusing on metropolitan areas or choosing locations for new regional offices.  

## Dataset

- `epa_air_quality.csv`
- **Source**: EPA
- **Observations**: 260
- **Contents**: AQI measurements collected from monitoring sites across 52 states/territories

## Technologies Used

- **Language**: Python
- **Environment**: Jupyter Notebook
- **Libraries**: `pandas`, `numpy`, `seaborn`, `scipy`

## Methods Applied

- **Confidence Intervals**:
  - 95% confidence intervals for average AQI by state to assess against the policy threshold
- **Hypothesis Testing**:
  - One-sample t-tests (state mean AQI vs. policy threshold)  
  - Two-sample independent t-tests (comparisons between states/counties)
 
## How to Run

1. Clone the repository or download the ZIP file from GitHub.
2. Open the project folder in your preferred environment.
3. Open `aqi_statistical_analysis.ipynb` and run the cells.

## Author

Developed by Juan Nathan.
