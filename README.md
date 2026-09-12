# Predicting Channel Attenuation Models for Hybrid RF/FSO Systems using Machine Learning

## 📌 Project Overview
This repository contains the research and machine learning implementation for predicting channel attenuation in Hybrid Radio Frequency (RF) and Free Space Optics (FSO) systems. By analyzing empirical data across multiple geographic locations, this project aims to understand and predict how varying weather conditions impact signal attenuation, ultimately optimizing the reliability of hybrid communication networks.

## 🚀 Key Features & Contributions
*   **Extensive Data Analysis:** Processed and analyzed over 600 days of empirical weather and signal data collected across multiple geographic locations.
*   **Targeted Modeling:** Developed 7 distinct weather-specific attenuation models and 1 overarching generic model to handle varying climatic conditions.
*   **Feature Engineering & Selection:** Implemented a robust feature selection methodology that reduced the predictor variables from 30+ down to under 10. This significantly reduced computational overhead while preserving model accuracy.
*   **Advanced Predictive Analytics:** Applied Random Forest regression to model complex, non-linear attenuation trends, outperforming traditional linear models.

## 📊 Results & Performance
*   **High Accuracy:** The Random Forest models achieved a **98% accuracy** in predicting attenuation trends.
*   **Beating Industry Standards:** The optimized feature selection and modeling approach improved the Root Mean Square Error (RMSE) accuracy over standard ITU (International Telecommunication Union) models by:
    *   **55.8% improvement** for RF systems.
    *   **44.4% improvement** for FSO systems.

## 🛠️ Technologies Used
*   **Language:** Python
*   **Machine Learning:** Scikit-Learn (Random Forest Regression, Feature Selection)
*   **Data Processing:** Pandas, NumPy
*   **Evaluation Metrics:** RMSE, Model Accuracy scoring

## 👤 Author
**Sushant Randhawa** 
*Master of Data Science Candidate | Business & Data Analyst*

---
*Feel free to explore the repository to view the data pipelines, feature selection methodology, and the regression models.*
