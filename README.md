🏦Forecast-of-Beta-bank's Customer loyalty-Sprint-8
📌 Objective
The goal of this project is to develop a machine learning model to help Beta Bank analyze customer loyalty and predict potential churn. By identifying customers who may be considering switching to another financial institution, the bank can proactively investigate the causes and implement strategies to improve customer retention.

📊 Data Preprocessing
Categorical Encoding: Binary variables were created for categorical features such as gender and geography.
Feature Selection: Columns like Surname, RowNumber, and CustomerID were removed as they did not contribute meaningful information to the model.
Standardization: All features were standardized to ensure equal importance during model training. This transformation was applied consistently across training, validation, and test datasets.
Class Balancing: Downsampling was used to address class imbalance, reducing the dominance of the majority class and improving model reliability.

🤖 Model Development
Multiple models were trained and validated to identify the best-performing approach.
The Random Forest Classifier was selected as the final model based on performance metrics.
Logistic Regression achieved the highest F1 score of 0.40 and an AUC-ROC score of 0.71, indicating good predictive capability.

✅ Results & Impact
The model successfully identifies customers at risk of churn.
Enables Beta Bank to take data-driven actions to retain valuable customers.
Provides a foundation for future enhancements, such as incorporating behavioral or transactional data.

🧰 Tools & Technologies
Python
Pandas, NumPy, Scikit-learn
Matplotlib, Seaborn (for visualization)

📁 Project Structure
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── models/                # Saved model files
├── src/                   # Source code for preprocessing and training
├── README.md              # Project overview and instructions
