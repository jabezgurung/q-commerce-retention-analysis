# Optimizing Quick-Commerce Retention: The Impact of Delivery Times

## 📌 Project Overview
This project evaluates the critical delivery time thresholds that trigger customer churn within the highly competitive Indian quick-commerce market (e.g., Blinkit, Zepto, Instamart). Using delivery logs and customer purchase histories, this study applies data cleansing pipelines and unsupervised machine learning to identify distinct behavioral segments based on delivery time sensitivity.
## 📊 Data Source
The raw dataset used for this analysis was sourced from Kaggle: [Insert Name of Kaggle Dataset Here](Insert the Kaggle URL here). The dataset contains raw delivery logs and customer purchase histories, which were subsequently cleansed and transformed using Python within this project.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Libraries:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (K-Means Clustering)
* **Data Visualization:** Matplotlib, Seaborn

## 📈 Methodology & Analytical Pipeline
1. **Data Cleansing & Transformation:** Handled missing values, standardized delivery timestamps, and engineered metrics for delivery delays and repeat purchase rates.
2. **Exploratory Data Analysis (EDA):** Leveraged Matplotlib and Seaborn to isolate correlation trends between fulfillment speeds and order frequencies.
3. **Unsupervised Machine Learning:** Implemented clustering algorithms to segment the user base into distinct profiles based on how drastically their purchasing behavior changed when deliveries were delayed.

## 💡 Key Business Recommendations
* **Segment-Specific Routing:** Users identified in the "High-Sensitivity" cluster experience a sharp decline in retention if deliveries exceed 15 minutes. Drivers should be dynamically prioritized to these segments during peak hours.
* **Expectation Management:** Implementing dynamic, accurate ETA displays during high-traffic windows reduces uncalculated churn by aligns expectations before the order is placed.
