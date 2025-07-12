# Deliverable 1: Data Collection, Cleaning, and Exploration

## Dataset Overview
- **Name**: Healthcare Dataset
- **Source**: Kaggle (uploaded for this project)
- **Size**: ~500+ records, with 8–10 attributes
- **Content**: Contains demographic and medical variables such as age, gender, symptoms, and medical history.

This dataset was chosen because it offers rich information suitable for predictive modeling, classification, clustering, and association rule mining tasks relevant to healthcare analytics.

---

## Data Cleaning & Preparation
Major cleaning steps performed:
- **Handling missing values**:
  - Numerical columns imputed with median values to reduce effect of outliers.
  - Categorical columns imputed with mode for consistency.
- **Duplicate removal**: Identified and dropped duplicate records.
- **Standardization**:
  - Converted categorical text to lowercase.
  - Cleaned inconsistent string formats.
  - Verified data types (e.g., categorical vs numerical).

---

## Exploratory Data Analysis (EDA)
Performed univariate and bivariate analyses to understand data distribution and feature relationships:
- Histogram of age distribution revealed skewness and presence of outliers in older age ranges.
- Bar chart of gender showed mild imbalance.
- Boxplot of age by gender highlighted differences in age spread.
- Correlation heatmap identified moderate correlations between some numerical features.

**Key insights:**
- Data has some outliers that may influence modeling.
- Slight imbalance in gender distribution to consider in future modeling.
- Certain features have moderate relationships, which may be useful for feature selection.

---

## ⚠Challenges & Solutions
| Challenge                          | Solution                                                        |
|-----------------------------------|-----------------------------------------------------------------|
| Missing data in several columns  | Used median/mode imputation depending on data type               |
| Outliers in numerical data       | Identified during EDA; flagged for treatment in next phase       |
| Inconsistent categorical strings | Standardized text (e.g., lowercase) and cleaned typos            |

---

## Next Steps
- Feature engineering to improve model performance.
- Encoding categorical variables.
- Proceed to regression and classification modeling (Deliverable 2).

---

**Course**: MSCS 634 – Advanced Data Mining  
**Deliverable**: 1 – Data Collection, Cleaning, and Exploration
