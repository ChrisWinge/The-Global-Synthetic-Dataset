# Betrayal of Trust: Analyzing Familial Recruitment in Minor Trafficking

## 📌 Project Overview
This project investigates the intersection of familial recruitment and coercive trafficking tactics, specifically focusing on minor victims. By analyzing the **Global Synthetic Dataset**, I explored how recruitment by family members correlates with higher levels of physical and psychological abuse compared to non-family recruiters.

## 📊 Data Source & Citation
The data used in this project is provided by the **Counter Trafficking Data Collaborative (CTDC)**, the first global data hub on human trafficking.

* **Dataset Name:** Global Synthetic Dataset
* **Provider:** Counter Trafficking Data Collaborative (CTDC)
* **Access Link:** [CTDC Global Synthetic Data](https://www.ctdatacollaborative.org/dataset/global-synthetic-dataset)

*Note: This is a synthetic dataset designed to protect the privacy and safety of victims while preserving the statistical properties of the original data.*

## 🚀 Key Technical Skills
- **Data Reshaping:** Used `pd.melt` and `pd.Categorical` to transform wide-format survey data for high-dimensional analysis.
- **Iterative Visualization:** Built automated `matplotlib` and `seaborn` subplot grids to analyze gender and sector distributions.
- **Time-Series Mapping:** Tracked the evolution of trafficking "Means of Control" over time.

## 📈 Key Findings
- **The Violence Gap:** Minors recruited by family members experience a confirmed rate of physical/psychological abuse significantly higher than those recruited by strangers or partners.
- **Gendered Sectors:** Familial recruitment patterns vary by gender, with distinct signatures appearing in sectors like Agriculture, Construction, and Prostitution.

## 🛠️ Installation
1. Clone the repository.
2. Install dependencies: `pip install pandas seaborn matplotlib`
3. Open `The Global Synthetic Dataset.ipynb` to view the analysis.
