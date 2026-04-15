# Water-Quality-of-Indian-Rivers-Analysis-and-Classification-ML
This project performs an in-depth analysis of water quality across various rivers in India using a dataset from 2023. It explores key parameters like Dissolved Oxygen (DO), Biochemical Oxygen Demand (BOD), pH levels, and Temperature to understand pollution trends and classify water safety.

## 📊 Project Overview
- **Data Cleaning:** Handling missing values, renaming complex headers, and stripping whitespace.
- **EDA & Visualization:** Heatmaps, monthly trends, and state-wise comparisons of pollution indicators.
- **Feature Engineering:** Calculation of Average DO, BOD, pH, and a custom 'Pollution Risk Score'.
- **Machine Learning:** 
    - **Classification:** Random Forest Classifier to categorize water into Good, Moderate, or Poor (Achieved ~100% accuracy on this specific dataset).
    - **Regression:** Random Forest Regressor to predict the Pollution Risk Score (R2 Score: 0.98).

## 🛠️ Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Platform:** Google Colab / Jupyter Notebook

## 📈 Key Findings
- Identified top polluted states based on BOD levels (e.g., Delhi, Uttar Pradesh).
- Visualized seasonal temperature trends and their correlation with oxygen levels.
- Determined key features driving water quality classification using Random Forest feature importance.

## 🚀 How to Use
1. Clone the repository.
2. Ensure the dataset `WaterQuality_Dataset.csv` is in the correct path.
3. Run the notebook cells sequentially to reproduce the analysis and models.

## 📄 License
This project is open-source and available under the MIT License.
