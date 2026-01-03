Fast Food Consumption & Health Impact Analysis


📊 Dashboard

🔍 Key Findings

• No Correlation: Surprisingly, this dataset shows no strong link between fast food frequency and BMI.

• Data Quality: The lack of expected biological correlations suggests this is likely a synthetic or practice dataset.

🛠 How to Run

1. Install libraries: pip install pandas seaborn matplotlib
2. Run the script: python analysis.py


📋Summary of Analysis

Project Objective

The primary goal of this analysis was to investigate the relationship between fast food consumption frequency and various health metrics, specifically Body Mass Index (BMI), self-reported Overall Health Score, and the prevalence of digestive issues.


Methodology

Dataset: 800 records containing demographic data (Age, Gender), lifestyle habits (Fast Food frequency, Sleep, Activity), and health indicators (BMI, Digestive Issues).

Tools: Python (Pandas for data manipulation, Seaborn/Matplotlib for visualization).

Technique: Exploratory Data Analysis (EDA) including univariate distribution checks, bivariate correlation analysis (Pearson coefficient), and categorical grouping.


Key Findings
A. Fast Food vs. BMI (Body Mass Index)

Hypothesis: Higher frequency of fast food meals leads to a higher BMI.

Result: The analysis revealed no significant correlation (Pearson correlation \approx -0.03). The scatter plot shows a random distribution of data points, indicating that in this specific dataset, eating more fast food does not statistically predict a higher BMI.


B. Impact on Perceived Health

Hypothesis: Individuals eating more fast food will report lower "Overall Health Scores."

Result: There was no observable trend. The correlation between Fast_Food_Meals_Per_Week and Overall_Health_Score was effectively zero (0.03). Participants eating 10+ fast food meals a week reported similar health scores to those eating 0-2 meals.


C. Physiological Inconsistencies

Observation: We analyzed the relationship between Average_Daily_Calories and BMI. Biologically, higher caloric intake is a primary driver of weight gain.

Result: The correlation was near zero (0.04). This absence of a fundamental biological link suggests the data does not reflect real-world physiological patterns.

Critical Conclusion & Data Quality Assessment

Based on the lack of correlation between biologically linked variables (e.g., Calories vs. BMI, Fast Food vs. Health), it is highly probable that this dataset is synthetic (randomly generated) rather than collected from real human subjects.


While the data served as an excellent resource for building an EDA pipeline and dashboarding, the specific health insights derived should not be treated as medically valid conclusions. Future analysis would require a dataset with validated medical records to draw accurate causal links.
