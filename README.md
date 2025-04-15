# House-Price-Prediction---Kaggle-Competition
This project utilizes machine learning models (Random Forest and XGBoost) to predict house prices in Ames, Iowa, based on 79 features. The goal is to improve pricing accuracy. By applying advanced regression techniques, the project demonstrates how data analysis can provide insights in an industry.

## Objectives

- **Primary Goal**: Develop a predictive model to forecast house prices in Ames, Iowa, based on 79 explanatory variables.
- **Business Objective**: Help Cardinal Heritage Realty regain market share by offering a competitive pricing tool that integrates tradition with machine learning.
- **Technical Objective**: Implement advanced regression techniques (Random Forest and XGBoost) to evaluate and improve the accuracy of house price predictions.

- Check out the Notebook:
![Notebook](https://github.com/SalazarHerna/House-Price-Prediction---Kaggle-Competition/blob/8a552c67054002c092e9d37dbeddcf860c93e409/Documents%20%26%20Code/Predicting%20House%20Prices_Kaggle%20Competition.ipynb)

## Key Outcomes

![Model Performance](https://github.com/SalazarHerna/House-Price-Prediction---Kaggle-Competition/blob/8a552c67054002c092e9d37dbeddcf860c93e409/Documents%20%26%20Code/Model%20Comparison%20-%20Price%20Prediction.jpeg)

- **Model Performance**:
  - **Random Forest Regression**: Achieved an R-squared of 90.7% and an RMSE of $26,713.91.
  - **XGBoost**: Produced similar results, but the Random Forest model was preferred due to its stable predictions and better interpretability.

## Insights

- **Feature Engineering**: Key features such as "Overall Quality," "GrLivArea" (above-ground living area), and "Total Baths" significantly impacted the predictions. These features were engineered based on both technical knowledge and market relevance.
- **Model Interpretability**: While both models (Random Forest and XGBoost) performed well, the Random Forest model was easier to interpret and align with business objectives, making it a practical choice for a traditional real estate business.
- **Residual Analysis**: The residual plots revealed that the model performed best for homes priced between $100,000 and $300,000, where most of the data points are concentrated. This insight helps refine future pricing strategies.

## Strategic Takeaway

By integrating machine learning with traditional real estate practices, the model offers an innovative yet practical solution for pricing properties. The project highlights the importance of feature selection, data quality, and the robustness of models like Random Forest in providing actionable business insights. 

## Tools Used
| **Tool/Technology** | **Description**                                                |
|---------------------|----------------------------------------------------------------|
| **Programming Language** | Python                                                    |
| **Libraries**        | - **Scikit-learn** (for Random Forest)                        |
|                     | - **XGBoost** (for gradient boosting)                          |
|                     | - **Pandas** (for data manipulation)                           |
|                     | - **Matplotlib/Seaborn** (for data visualization)              |
|                     | - **NumPy** (for numerical operations)                         |
| **Data Handling**    | CSV data preprocessing, handling missing values, encoding categorical variables |
| **Visualization**    | Distribution plots, feature importance, residual plots         |

---
## Steps Taken

1. **Data Preparation**
2. **Feature Engineering**
3. **Model Development**
4. **Model Evaluation**
5. **Business Adjustment**
6. **Final Predictions**

---
## Conclusions or Recommendations

- **Conclusion**: The Random Forest model outperforms XGBoost in this application due to its stability and interpretability. The model accurately predicts house prices, offering a robust solution for predicting house prices.
- **Recommendations**:
  - For real estate businesses: Consider adopting machine learning models for dynamic pricing that can be continuously updated with new data.
  - For future iterations: Incorporate additional data sources like local market trends or real-time property features to further refine the pricing model.
  - Explore model deployment using cloud solutions (e.g., AWS or Google Cloud) for scalability and easy integration into real-time business processes.
