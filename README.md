{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Fast Food Consumption & Health Impact Analysis\n",
    "\n",
    "## 📌 Project Overview\n",
    "This project performs an Exploratory Data Analysis (EDA) on a dataset linking fast food consumption habits to health metrics such as BMI, Overall Health Score, and Digestive Issues. The goal was to identify if higher fast food frequency correlates with negative health outcomes in this specific population sample.\n",
    "\n",
    "## 📊 Dashboard\n",
    "![Dashboard](images/dashboard.png)\n",
    "*Figure 1: Comprehensive view of data distributions, relationships, and health metrics.*\n",
    "\n",
    "## 🔍 Key Findings\n",
    "After rigorous statistical analysis and visualization, the following insights were derived from the dataset:\n",
    "\n",
    "1.  **Independence of Variables**: Contrary to general medical knowledge, this specific dataset shows **no significant linear correlation** between `Fast_Food_Meals_Per_Week` and `BMI` (Pearson correlation $\\approx -0.03$).\n",
    "2.  **Health Score Anomaly**: Self-reported \"Overall Health Scores\" appeared consistent across all groups, regardless of fast food intake.\n",
    "3.  **Data Quality Insight**: The lack of expected physiological correlations (e.g., Caloric Intake vs. BMI correlation is near zero) suggests this dataset may be **synthetic or randomized**. It serves as a case study in identifying data quality issues before building predictive models.\n",
    "\n",
    "## 🛠️ Methodology\n",
    "The analysis was conducted using Python with the following steps:\n",
    "1.  **Data Cleaning**: Checked for missing values and inconsistencies.\n",
    "2.  **Univariate Analysis**: Plotted distributions for Age, BMI, and Fast Food frequency.\n",
    "3.  **Bivariate Analysis**: Used scatter plots and box plots to test hypotheses (e.g., \"Does more fast food equal higher BMI?\").\n",
    "4.  **Correlation Matrix**: Calculated Pearson correlation coefficients for all numerical features.\n",
    "\n",
    "## 💻 How to Run This Project\n",
    "To reproduce the analysis, follow these steps:\n",
    "\n",
    "1.  **Clone the repository**\n",
    "    ```bash\n",
    "    git clone [https://github.com/yourusername/fast-food-analysis.git](https://github.com/yourusername/fast-food-analysis.git)\n",
    "    cd fast-food-analysis\n",
    "    ```\n",
    "\n",
    "2.  **Install Dependencies**\n",
    "    ```bash\n",
    "    pip install -r requirements.txt\n",
    "    ```\n",
    "\n",
    "3.  **Run the Analysis Script**\n",
    "    ```bash\n",
    "    python analysis.py\n",
    "    ```\n",
    "\n",
    "## 📂 Repository Structure\n",
    "* `data/`: Contains the raw CSV file.\n",
    "* `images/`: Generated plots and dashboards.\n",
    "* `analysis.py`: Main Python script for EDA.\n",
    "* `README.md`: Project documentation.\n",
    "\n",
    "## 📜 License\n",
    "This project is open-source and available under the MIT License.\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.1+"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
