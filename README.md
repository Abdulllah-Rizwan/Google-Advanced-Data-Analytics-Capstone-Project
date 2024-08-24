# Employee Retention Prediction using Random Forest and Decision Trees
A predictive analysis project on identifying factors influencing employee turnover using machine learning models.

# Project Overview
This project seeks to predict employee retention at Salifort Motors using various machine learning techniques. Leveraging employee-related data, we employed decision trees and random forest algorithms to predict which employees are most likely to leave the company. The goal was to identify the most influential factors behind employee turnover, which can guide HR in taking actionable steps to improve retention. The random forest model outperformed the decision tree model in predictive accuracy, offering robust insights.

# Business Understanding
Salifort Motors has faced challenges with employee retention and wanted to address the root causes behind their high turnover rates. The business stakeholders needed to understand which factors most significantly contribute to employees leaving the company and how they could reduce attrition rates. By identifying key factors such as workload, evaluation frequency, tenure, and overwork, this project provides a foundation for HR to implement better policies to improve job satisfaction and reduce turnover.

# Data Understanding
The data used in this project consisted of employee records including metrics such as 'last_evaluation', 'number_project', 'overworked', 'tenure', and others that could contribute to employee attrition. The dataset was a historical record spanning over several years. Some limitations included the exclusion of employee sentiment data and external economic factors which may also influence turnover. Exploratory analysis revealed the most critical features, such as the number of projects, last evaluation scores, and work conditions.

# Modeling and Evaluation
We utilized both decision trees and random forest classifiers to build predictive models. The random forest model performed slightly better than the decision tree model due to its ability to handle more complex feature interactions. Feature importance metrics revealed that 'last_evaluation', 'number_project', and 'overworked' were the top three factors driving employee turnover. The evaluation metrics, including accuracy, precision, and recall, showed that the random forest model was more reliable for predicting employee exit.

# Conclusion
Based on our analysis, we recommend that Salifort Motors caps the number of projects assigned to employees and ensures a better work-life balance to prevent burnout. Additionally, recognizing employees who consistently meet expectations and further investigating why long-tenured employees are leaving will help improve retention. Future steps involve integrating employee satisfaction surveys and exploring deeper connections between specific departmental challenges and turnover rates.
