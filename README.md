# Customer Churn Prediction
A developed ML model that helps predict which customers are likely to churn based on historical data.
<hr size="10">

## 🎯 Business Problem

Adventure Hardware Group (AHG) is a major global manufacturer of bikes and bike accessories across America, Europe, and Asia. As AHG builds a unified data architecture, its key priority is reducing customer churn. AHG aims to spot early warning signs of disengagement and understand what drives customers to leave or switch to competitors. Through using and integrating these data sources, the company wanted a solution that will help retain customers and maximise profits.

## 📁 Repository Structure
| File | Description | 
| --- | --- |
| Customer_Churn_Model.ipynb | Notebook file containing the full end-to-end ML churn model development. (Including Data preprocessing, cleaning, transformation, EDA, RFM Clustering, Feature engineering, Model development, evalution and hyperparameter tuning)| 
| Customer churn model report.pdf | Full report on the development and recommendations from the Churn Model project |
|images | Screenshots of project insights or results |

## ⚒️ Tools & Programming Languages
- SQL (Microsoft SQL Server)
- Python
- MS Office

## 🔑 Key Insights
- After comparing the performance of multiple ML models, Linear Discriminant Analysis (LDA) was chosen as the best model algorithm as it scored the highest avg f1_score (0.85) at low standard deviations per run.

![report Screenshot](images/Churn%20model%20performance%20results.png)
