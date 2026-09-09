# 🌾 Seasonal Agriculture Performance Analysis

### Major Data Analytics Project | VOIS AICTE Batch1 2026-2027

**Domain:** Agriculture  
**Project Theme:** Seasonal Agriculture Performance  
**Tools & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy  
**Platform:** Google Colab  
**Internship Program:** Edunet Foundation × VOIS for Tech (Vodafone Idea Foundation) — Data Analytics  
**College:** Sitamarhi Institute of Technology  
**Student:** Nishant Kumar

---

## 📌 Project Goal

The goal of this project is to analyze seasonal agricultural performance using farm-level data.

The analysis focuses on understanding how agricultural performance varies across different seasons by examining environmental conditions, farming practices, resource usage, crop production, yield, water usage, disease and pest risk, costs, revenue, and profit.

The project uses data analysis, statistical methods, visualization techniques, and comparative analysis to discover meaningful patterns and generate evidence-based insights.

---

## 1. Introduction

Agriculture is strongly influenced by seasonal conditions, environmental factors, farming practices, resource availability, crop selection, and economic factors.

This project analyzes an agricultural dataset containing information about farms, crops, seasons, geographical regions, environmental conditions, irrigation methods, resource usage, production, yield, market prices, costs, revenue, profit, and disease/pest risk.

The purpose of the analysis is to identify important patterns and variations in agricultural performance across seasons and other relevant categories.

---

## 2. Problem Statement

Agricultural performance can vary significantly across different seasons due to differences in environmental conditions, farming practices, resource usage, crop selection, and economic factors.

However, raw agricultural data does not directly reveal these patterns.

Therefore, the problem is to analyze the available agricultural dataset and identify meaningful seasonal differences, relationships, trends, unusual observations, and performance patterns using appropriate data analytics and statistical techniques.

The findings can help in understanding agricultural performance and support evidence-based decision-making and future investigation.

---

## 3. Importance of the Problem

Understanding agricultural performance through data analytics is important because it can help to:

- Identify seasonal variations in agricultural performance
- Compare crop performance across different seasons
- Understand differences in yield and production
- Analyze resource and water usage
- Examine economic performance such as cost, revenue, and profit
- Identify disease and pest risk patterns
- Investigate relationships between environmental and agricultural variables
- Detect unusual observations and potential outliers
- Support evidence-based agricultural planning
- Provide useful directions for future agricultural analysis

---

## 4. Objectives

The main objectives of this project are:

- Understand the structure and characteristics of the agricultural dataset.
- Check and improve the quality of the data.
- Identify missing values and handle them appropriately.
- Identify and handle duplicate records.
- Examine data types and variable distributions.
- Perform descriptive and statistical analysis.
- Perform univariate analysis.
- Perform bivariate analysis.
- Perform multivariate analysis.
- Perform correlation analysis.
- Investigate outliers and unusual observations.
- Compare agricultural performance across seasons.
- Analyze crop-wise and state-wise performance.
- Examine irrigation and resource usage patterns.
- Analyze disease and pest risk.
- Perform additional student-driven analyses.
- Generate meaningful evidence-based insights.
- Provide practical recommendations based only on the observed data.
- Discuss important limitations of the analysis.

---

## 5. Dataset Description

**Dataset File:** `seasonal_agriculture_performance_dataset.csv`

**Number of Records:** 4000 farm-level entries

**Number of Columns:** 28

| Column | Description |
|---|---|
| Farm_ID | Unique identifier for each farm |
| State | State where the farm is located |
| District | District where the farm is located |
| Crop | Type of crop grown |
| Season | Season of cultivation (Kharif / Rabi / Zaid) |
| Farm_Area_Hectares | Total farm area |
| Rainfall_mm | Rainfall received in millimetres |
| Avg_Temperature_C | Average temperature in °C |
| Humidity_pct | Humidity percentage |
| Sunlight_Hours_Day | Average sunlight hours per day |
| Soil_pH | Soil pH level |
| Soil_Moisture_pct | Soil moisture percentage |
| Nitrogen_kg_ha | Nitrogen content in kg/ha |
| Phosphorus_kg_ha | Phosphorus content in kg/ha |
| Potassium_kg_ha | Potassium content in kg/ha |
| Irrigation_Method | Type of irrigation used |
| Fertilizer_kg_ha | Fertilizer applied in kg/ha |
| Pesticide_Litre_ha | Pesticide applied in litre/ha |
| Seed_Quality_Score | Seed quality rating |
| Yield_Tonnes_Ha | Crop yield in tonnes/ha |
| Production_Tonnes | Total production in tonnes |
| Market_Price_INR_Tonne | Market price in INR per tonne |
| Total_Cost_INR | Total cost incurred in INR |
| Revenue_INR | Revenue generated in INR |
| Profit_INR | Net profit in INR |
| Water_Used_m3 | Water consumption in cubic metres |
| Water_Efficiency_t_per_1000m3 | Water-use efficiency |
| Disease_Pest_Risk_pct | Disease and pest risk percentage |

---

## 6. Data Analysis Performed

The project includes the following major analysis stages:

### 6.1 Data Loading

- Dataset loaded successfully using Pandas.
- Dataset shape and structure were examined.
- Top 5 rows were inspected.
- Column names and data types were reviewed.

### 6.2 Data Quality Analysis

- Missing values were identified.
- Duplicate records were checked.
- Data types were examined.
- Unusual and extreme values were investigated.
- Appropriate data-cleaning procedures were applied.

### 6.3 Descriptive Statistical Analysis

Statistical summaries were generated to understand:

- Mean
- Median
- Standard deviation
- Minimum and maximum values
- Quartiles
- Distribution of numerical variables

### 6.4 Univariate Analysis

Individual variables were analyzed using suitable visualizations.

Examples include:

- Crop distribution
- Season distribution
- Agricultural yield distribution
- Farm profit distribution
- Rainfall distribution
- Other numerical and categorical variable distributions

### 6.5 Bivariate Analysis

Relationships and differences between two variables were investigated.

Examples include:

- Season vs Yield
- Season vs Profit
- Crop vs Yield
- Irrigation Method vs Water Usage
- Irrigation Method vs Profit
- State vs Yield

### 6.6 Multivariate Analysis

Multiple variables were analyzed together to understand combined patterns involving:

- Season
- Crop
- Region
- Environmental conditions
- Irrigation
- Resources
- Yield
- Production
- Economic performance
- Disease/Pest Risk

### 6.7 Correlation Analysis

Correlation analysis was performed to identify relationships among relevant numerical variables.

The analysis helps identify variables that show positive, negative, or weak relationships.

Correlation indicates association and should not be interpreted as proof of causation.

### 6.8 Outlier Analysis

Potential outliers were investigated using statistical and visual methods.

Extreme observations were examined particularly for:

- Yield
- Profit
- Rainfall
- Resource usage
- Other numerical variables

Outliers were interpreted carefully because extreme values may represent genuine observations rather than errors.

---

## 7. Key Analytical Questions

The project investigates questions such as:

- How does agricultural performance vary across seasons?
- Which season has the highest average yield?
- Which season has the highest average profit?
- How is crop performance distributed in the dataset?
- Which states show higher average agricultural yield?
- How does irrigation method relate to water usage?
- How does irrigation method relate to profit?
- How does disease/pest risk vary across crops?
- What relationships exist between farm area and production?
- What relationships exist between environmental conditions and agricultural performance?
- Are there unusual or extreme observations?
- What meaningful patterns can be identified from the data?
- What recommendations can reasonably be made from the observed evidence?

---

## 8. Major Findings

The analysis produced several important findings.

### Seasonal Average Yield

| Season | Average Yield (Tonnes/Ha) |
|---|---:|
| Kharif | 5.63 |
| Rabi | 5.04 |
| Zaid | 4.64 |

Kharif has the highest average yield among the three seasons, followed by Rabi and Zaid.

### Seasonal Average Profit

| Season | Average Profit (INR) |
|---|---:|
| Kharif | ₹178,914.65 |
| Rabi | ₹87,689.47 |
| Zaid | -₹24,804.82 |

Kharif shows the highest average profit, while Zaid shows a negative average profit in the analyzed dataset.

### Crop-wise Average Yield

| Crop | Average Yield (Tonnes/Ha) |
|---|---:|
| Sugarcane | 46.64 |
| Maize | 2.71 |
| Rice | 2.43 |
| Wheat | 2.11 |
| Chilli | 1.54 |
| Groundnut | 1.32 |
| Cotton | 1.23 |
| Pulses | 0.92 |

Sugarcane has a substantially higher average yield than the other crops in the dataset.

### State-wise Average Yield

| State | Average Yield (Tonnes/Ha) |
|---|---:|
| Punjab | 6.12 |
| Karnataka | 5.69 |
| Gujarat | 5.66 |
| Telangana | 5.04 |
| Maharashtra | 5.02 |
| Madhya Pradesh | 4.99 |
| Tamil Nadu | 4.88 |
| Andhra Pradesh | 4.63 |

Punjab records the highest average yield among the listed states.

### Irrigation-wise Average Water Usage

| Irrigation Method | Average Water Usage (m³) |
|---|---:|
| Flood | 8026.47 |
| Sprinkler | 6208.26 |
| Drip | 5918.75 |
| Rainfed | 3549.55 |

Flood irrigation has the highest average water usage, while rainfed farming has the lowest.

### Irrigation-wise Average Profit

| Irrigation Method | Average Profit (INR) |
|---|---:|
| Drip | ₹219,626.00 |
| Sprinkler | ₹91,121.08 |
| Rainfed | ₹79,050.37 |
| Flood | ₹73,354.02 |

Drip irrigation has the highest average profit in the analyzed dataset.

### Crop-wise Disease/Pest Risk

| Crop | Average Disease/Pest Risk (%) |
|---|---:|
| Wheat | 47.85 |
| Pulses | 46.57 |
| Rice | 46.50 |
| Groundnut | 46.29 |
| Chilli | 46.06 |
| Cotton | 45.97 |
| Maize | 45.54 |
| Sugarcane | 45.40 |

The disease/pest risk values are relatively close across crops, with Wheat showing the highest average risk among the listed crops.

### Farm Area vs Production

The observed correlation between farm area and production is approximately:

**Correlation = 0.198**

This indicates a weak positive linear association between farm area and production in the analyzed dataset.

---

## 9. Student-Driven Analysis

Additional analyses were performed beyond the standard analysis sections.

### Student Analysis 1 – Irrigation Method and Profit

**Question:** Which irrigation method is associated with higher average farm profit?

The analysis compared average profit across irrigation methods.

The results showed that Drip irrigation had the highest average profit among the irrigation methods present in the dataset.

This analysis is relevant because irrigation is an important agricultural resource and comparing economic outcomes across irrigation methods can help identify patterns worth further investigation.

### Student Analysis 2 – State-wise Agricultural Performance

**Question:** How does average agricultural yield differ across states?

State-wise average yield was calculated and compared.

Punjab showed the highest average yield among the listed states, while Andhra Pradesh showed the lowest average yield among the listed states.

This analysis is relevant because agricultural performance may vary geographically, and regional comparisons can reveal areas that require further investigation.

### Student Analysis 3 – Crop-wise Disease/Pest Risk

**Question:** Which crops show higher average disease and pest risk?

Average Disease/Pest Risk percentage was calculated for each crop.

Wheat showed the highest average disease/pest risk, while Sugarcane showed the lowest average risk among the listed crops.

This analysis is relevant because disease and pest risk is an important agricultural factor that may affect crop performance and should be considered when interpreting agricultural outcomes.

---

## 10. Visualizations

The project uses visualizations to make agricultural patterns easier to understand.

Major visualizations include:

- Crop distribution bar chart
- Season distribution bar chart
- Agricultural yield histogram
- Farm profit histogram
- Rainfall distribution histogram
- Seasonal yield comparison
- Seasonal profit comparison
- Crop-wise yield comparison
- State-wise yield comparison
- Irrigation-wise water usage comparison
- Irrigation-wise profit comparison
- Disease/Pest risk comparison
- Correlation analysis and heatmaps
- Bivariate and multivariate visualizations

These visualizations help communicate patterns, differences, distributions, relationships, and unusual observations.

---

## 11. Key Insights

### Insight 1 – Seasonal Yield Difference

**Observation:** Kharif has the highest average yield at approximately 5.63 tonnes/ha.

**Evidence:** Seasonal average yield analysis.

**Interpretation:** Agricultural yield varies across seasons, with Kharif showing the highest average yield in this dataset.

**Limitation:** This does not establish that season alone causes the difference in yield.

### Insight 2 – Seasonal Profit Difference

**Observation:** Kharif has the highest average profit, while Zaid has a negative average profit.

**Evidence:** Seasonal average profit analysis.

**Interpretation:** Economic performance differs considerably across seasons.

**Limitation:** The analysis does not establish why the profit differences occur.

### Insight 3 – Sugarcane Yield

**Observation:** Sugarcane has an average yield of approximately 46.64 tonnes/ha.

**Evidence:** Crop-wise average yield analysis.

**Interpretation:** Sugarcane has substantially higher yield values than the other crops in the dataset.

**Limitation:** Yield values are crop-specific and should not be directly interpreted as overall crop superiority without considering crop type and measurement context.

### Insight 4 – Regional Yield Variation

**Observation:** Punjab records the highest average yield among the listed states.

**Evidence:** State-wise average yield analysis.

**Interpretation:** Average agricultural yield varies across geographic regions.

**Limitation:** The observed difference may be associated with multiple factors and cannot be attributed to state alone.

### Insight 5 – Water Usage by Irrigation Method

**Observation:** Flood irrigation has the highest average water usage.

**Evidence:** Irrigation-wise average water usage analysis.

**Interpretation:** Different irrigation methods show noticeable differences in average water consumption.

**Limitation:** The analysis does not establish that irrigation method alone determines water usage.

### Insight 6 – Irrigation and Profit

**Observation:** Drip irrigation has the highest average profit in the dataset.

**Evidence:** Irrigation-wise average profit analysis.

**Interpretation:** Drip irrigation is associated with higher average profit in the observed data.

**Limitation:** This is an association and does not prove that drip irrigation directly causes higher profit.

### Insight 7 – Disease/Pest Risk

**Observation:** Disease/pest risk values are relatively similar across the analyzed crops.

**Evidence:** Crop-wise Disease/Pest Risk analysis.

**Interpretation:** No extremely large difference in average disease/pest risk is visible among the listed crops.

**Limitation:** Average risk does not describe individual farm-level variation or specific disease causes.

### Insight 8 – Farm Area and Production

**Observation:** Farm area and production show a correlation of approximately 0.198.

**Evidence:** Correlation analysis.

**Interpretation:** There is a weak positive linear association between farm area and production.

**Limitation:** Correlation does not imply causation and does not capture all factors affecting production.

---

## 12. Recommendations

The recommendations below are based only on patterns observed in the analyzed dataset.

- **Consider seasonal differences:** Since Kharif shows the highest average yield and profit, seasonal performance should be considered during agricultural planning.
- **Investigate Zaid season performance:** The negative average profit observed for Zaid suggests that its cost, revenue, crop mix, and resource usage should be examined further.
- **Investigate drip irrigation:** Drip irrigation shows the highest average profit in the dataset and should be examined further in relation to crop type, water usage, and cost.
- **Review high water usage:** Flood irrigation has the highest average water usage, so its resource-use pattern can be investigated further.
- **Study regional differences:** State-wise yield differences suggest that regional conditions and farming practices deserve additional investigation.
- **Consider disease/pest risk:** Crops with relatively higher observed disease/pest risk should be considered carefully in future agricultural analysis.
- **Use correlation carefully:** Relationships between variables should be investigated further before making operational decisions because correlation alone does not establish causation.
- **Conduct deeper crop-season analysis:** Future analysis can compare individual crops across Kharif, Rabi, and Zaid seasons to obtain more specific insights.

---

## 13. Limitations

The analysis has several limitations:

- The dataset represents the available observations and may not represent all agricultural conditions.
- Observed relationships are associations and should not be interpreted as causal relationships.
- Average values can hide farm-level variation.
- Extreme values may influence some statistical results.
- The analysis does not include external market, policy, or socio-economic information.
- State-level differences cannot be attributed to geography alone.
- Irrigation-profit differences cannot be interpreted as proof that one irrigation method causes higher profit.
- Further investigation with larger and more detailed datasets would be required for stronger conclusions.

---

## 14. Future Scope

Future work can extend this project by:

- Performing crop-season level analysis
- Building predictive models for yield and profit
- Forecasting seasonal agricultural performance
- Studying weather and environmental impacts in greater detail
- Applying machine learning techniques
- Developing an agricultural performance dashboard
- Performing time-series analysis with historical agricultural data
- Investigating regional and district-level patterns
- Studying water efficiency and resource optimization
- Developing early-warning analysis for disease and pest risk
- Integrating additional market and weather datasets

---

## 15. Expected Outcomes

The project provides:

- A structured understanding of the agricultural dataset
- Data quality and preprocessing analysis
- Descriptive and statistical analysis
- Univariate, bivariate, and multivariate analysis
- Correlation analysis
- Outlier investigation
- Seasonal comparisons
- Crop-wise and state-wise comparisons
- Resource and irrigation analysis
- Disease/pest risk analysis
- Student-driven analytical findings
- Evidence-based insights
- Practical recommendations
- Discussion of analytical limitations
- Directions for future investigation

---

## 16. Project Workflow

The overall project workflow followed these steps:

**Dataset → Data Loading → Data Understanding → Data Cleaning → Statistical Analysis → Univariate Analysis → Outlier Analysis → Bivariate Analysis → Multivariate Analysis → Correlation Analysis → Seasonal Comparison → Student-Driven Analysis → Key Insights → Recommendations → Conclusion**

---

## 17. Tools & Technologies

### Programming Language
- **Python 3**

### Data Analysis
- **Pandas** – Data loading, cleaning, transformation, grouping and aggregation
- **NumPy** – Numerical computations and array operations
- **SciPy** – Statistical analysis

### Data Visualization
- **Matplotlib** – Data visualization and plotting
- **Seaborn** – Statistical data visualization

### Development Platform
- **Google Colab** – Cloud-based Python notebook environment used for analysis, execution, visualization, and documentation

### Dataset Format
- **CSV** – Agricultural source dataset

---

## 18. How to Run the Project

The project was developed and analyzed using **Google Colab**.

### Option 1 – Google Colab

1. Open Google Colab.
2. Upload the file:
   `Seasonal_Agriculture_Performance_Data_Analytics.ipynb`
3. Upload the dataset:
   `seasonal_agriculture_performance_dataset.csv`
4. Make sure the dataset path used in the notebook is correct.
5. Run the notebook cells sequentially using **Runtime → Run all**.

### Option 2 – Local Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter


## 19. Repository Structure

```text
Seasonal_Agriculture_Performance_Analysis/
│
├── Seasonal_Agriculture_Performance_Data_Analytics.ipynb
│   └── Main data analysis notebook
│
├── seasonal_agriculture_performance_dataset.csv
│   └── Agricultural source dataset
│
├── Major_Project_Seasonal_Agriculture_Performance_Analysis_.pdf
│   └── Project brief / problem statement
│
├── Major_Project_PPT.pptx
│   └── Project presentation
│
├── vois_offer_letter.pdf
│   └── AICTE Internship Offer Letter
│
└── README.md
    └── Project documentation

## 20. Project Presentation

The project presentation includes:

- Project Title
- Problem Statement
- Project Description
- End Users
- Technology Used
- Dataset Overview
- Data Analysis
- Results and Visualizations
- Key Findings
- Recommendations
- Future Scope
- Conclusion
- GitHub Repository
- Internship-related information

---

## 21. Internship Details

**Program:** VOIS for Tech — Data Analytics Internship  
**Organization:** Edunet Foundation × Vodafone Idea Foundation  
**Batch:** VOIS AICTE Batch1 2026-2027  
**Duration:** 10th August 2026 – 10th September 2026  
**Domain:** Data Analytics

---

## 22. Conclusion

The Seasonal Agriculture Performance Analysis project demonstrates how data analytics can be used to understand agricultural performance across different seasons and categories.

The analysis identified differences in seasonal yield and profit, crop-wise yield variation, state-wise yield differences, irrigation-wise water usage and profit patterns, disease/pest risk levels, and relationships between selected agricultural variables.

The results provide a data-driven view of the available agricultural observations. However, the findings represent associations within the dataset and should not be interpreted as proof of causation.

The project also highlights how statistical analysis and visualization can support agricultural performance evaluation and provide directions for future investigation, predictive modeling, resource analysis, and decision-making.

---

## 23. License

This project is created for educational purposes as part of the **VOIS AICTE Data Analytics Internship Program**.

---

## 👨‍💻 Developed By

**Nishant Kumar**  
Sitamarhi Institute of Technology

**VOIS AICTE Batch1 2026-2027**
