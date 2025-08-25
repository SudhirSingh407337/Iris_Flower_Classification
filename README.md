# 🌸 Iris Flower Classification  

## 📌 Project Overview  
This project demonstrates how to **classify iris flowers** based on their **sepal and petal measurements** using machine learning techniques.  

- 🛠 **Feature Engineering** – applied techniques such as one-hot encoding, polynomial feature generation, and feature scaling  
- 🤖 **Machine Learning** – trained classification models to distinguish between different iris species  
- 🎯 **Goal** – improve prediction performance and understand how feature transformations impact model accuracy  


## Dataset
The classic Iris dataset contains 150 samples of iris flowers, each with four features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Each flower is labeled as one of three species:
- Iris setosa
- Iris versicolor
- Iris virginica

## Key Techniques Implemented
1. **Data Exploration & Visualization**
   - Distribution analysis
   - Correlation analysis
   - Feature relationship visualization
   - Box plots for feature distributions

2. **Data Preprocessing**
   - Train-test split with stratification
   - One-hot encoding for target variables
   - Polynomial feature generation (degree 2)
   - Feature scaling using StandardScaler

3. **Model Training & Evaluation**
   - Logistic Regression classifier
   - Random Forest classifier
   - Classification reports and confusion matrices
   - Comparative model performance analysis

4. **Feature Importance Analysis**
   - Random Forest feature importance
   - Logistic Regression coefficient analysis
   - Comparison of feature rankings between models

## Results
Both models achieve high accuracy in classifying iris species, with the feature engineering steps contributing significantly to model performance. The polynomial feature transformation helps capture non-linear relationships between measurements, while scaling ensures all features contribute appropriately to the models.

The analysis shows which features (including generated polynomial features) are most important for distinguishing between iris species, providing insights into the botanical characteristics that best differentiate these flowers.

## Requirements
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Use
1. Clone this repository
2. Ensure you have all required packages installed
3. Open the Jupyter notebook `iris_classification.ipynb`
4. Run the cells sequentially to see the analysis and results

## File Structure
- `iris_classification.ipynb` - The main Jupyter notebook containing all analysis and code
- `IRIS.csv` - The dataset file
- `README.md` - This file with project information

## Key Insights
- Feature engineering significantly improves model performance
- Polynomial features capture important non-linear relationships
- Both Logistic Regression and Random Forest models perform well, highlighting the effectiveness of the preprocessing approach
- The models show excellent separation of iris species, especially for Iris setosa
