# Seasonal Agriculture Performance Analysis

## Major Project – VOIS AICTE Batch 1 2026–2027

### Project Overview
This project analyzes agricultural data across different seasons to identify meaningful patterns, trends, relationships and differences in agricultural performance.

The analysis focuses on **Kharif, Rabi and Zaid** seasons and examines yield, profit, irrigation, crop-level performance, environmental conditions and numerical relationships.

## Dataset
File: `seasonal_agriculture_performance_dataset.csv`

- Records: **4,000**
- Variables: **28**
- Seasons: **Kharif, Rabi, Zaid**
- Missing cells: **120**
- Duplicate rows: **0**

## Objectives
- Explore and understand the dataset.
- Check data quality and prepare the data for analysis.
- Compare agricultural performance across seasons.
- Analyze seasonal yield and profitability.
- Investigate irrigation-method performance.
- Compare crop performance across seasons.
- Examine relationships between numerical factors and yield.
- Generate evidence-based conclusions and recommendations.

## Analytical Questions
1. How does agricultural yield vary across seasons?
2. How does average profit vary across seasons?
3. Which irrigation method is associated with the highest average yield and profit?
4. How does crop performance differ across seasons?
5. Which numerical factors have the strongest relationship with yield?
6. Are there notable differences in rainfall, temperature, water efficiency or disease/pest risk between seasons?

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analysis Workflow
1. Load dataset
2. Explore structure and data types
3. Check missing values and duplicates
4. Generate descriptive statistics
5. Analyze season distribution
6. Compare seasonal yield
7. Compare seasonal profit
8. Analyze irrigation methods
9. Analyze crop-level seasonal patterns
10. Perform correlation analysis
11. Compare environmental/resource variables
12. Generate findings, conclusions and recommendations

## Key Findings

### Seasonal Yield
| Season | Average Yield (Tonnes/Ha) |
|---|---:|
| Kharif | 5.64 |
| Rabi | 5.08 |
| Zaid | 4.67 |

Kharif has the highest average yield, while Zaid has the lowest.

### Seasonal Profit
| Season | Average Profit |
|---|---:|
| Kharif | ₹178,915 |
| Rabi | ₹87,689 |
| Zaid | -₹24,805 |

Kharif has the highest average profit. Zaid has negative average profitability in the available dataset.

### Irrigation
Drip irrigation has the highest average yield at approximately **6.62 tonnes/ha** and the highest average profit at approximately **₹219,626** among the irrigation methods analyzed.

This is an observed association and should not be interpreted as proof of causation.

### Crop-Level Pattern
Sugarcane has a substantially higher yield scale than the other crops. Its Kharif average yield is approximately **53.46 tonnes/ha**.

## Conclusion
The analysis demonstrates that agricultural performance varies across seasons. Kharif shows the strongest average yield and profitability, while Zaid shows lower yield and negative average profit. Irrigation method and crop type also show important differences in agricultural outcomes.

## Future Scope
- Machine-learning-based crop-yield prediction
- Seasonal profit forecasting
- Real-time weather and market-price integration
- Soil, fertilizer and pesticide analysis
- Interactive agricultural dashboards
- Geographical visualization
- Disease and pest risk early-warning systems

## Repository Structure
```text
Seasonal-Agriculture-Performance-Analysis/
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── VOIS_Major_Project_Seasonal_Agriculture_PPT.pptx
├── README.md
└── outputs/
```

## Author
**Student Name:** SAMRUDDHI PRADEEP REPAL   
**AICTE STU ID:** STU6a203feff1e631780498415  

## Project Title
**Seasonal Agriculture Performance Analysis**
