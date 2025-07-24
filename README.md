# Parkinson's Disease Classification and Clustering

This project focuses on preprocessing and analyzing the Parkinson's Disease dataset. It includes classification tasks using various machine learning algorithms and unsupervised clustering using KMeans.

## 📁 Dataset

- **Name:** `Parkinson.csv`
- The dataset contains patient voice measurements which are useful for detecting Parkinson’s Disease.

## 🔧 Project Structure

1. **Data Cleaning**  
   - Handling missing values using `SimpleImputer`.
   - Removing outliers using `winsorization`.
   - Encoding categorical values using `LabelEncoder`.

2. **Exploratory Data Analysis (EDA)**  
   - Summary statistics and visualizations with `Seaborn` and `Matplotlib`.

3. **Feature Scaling**  
   - Features were standardized using `StandardScaler`.

4. **Model Training & Evaluation**  
   - **Logistic Regression**
   - **K-Nearest Neighbors (KNN)** with `GridSearchCV`
   - Cross-validation and evaluation metrics:
     - Accuracy
     - Confusion Matrix
     - Classification Report

5. **Unsupervised Learning**  
   - KMeans clustering with silhouette score to evaluate clustering quality.

## 🛠 Libraries Used

- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`

## 📊 Model Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Silhouette Score (for clustering)

## 🚀 How to Run

1. Clone the repository.
2. Make sure `Parkinsons_dirty.csv` is in the working directory.
3. Open `final_project.ipynb` using Jupyter Notebook.
4. Run all cells sequentially to see the analysis and results.

## 🧠 Future Work

- Test with other models like SVM or Random Forest.
- Perform feature selection to improve performance.
- Integrate PCA for dimensionality reduction.
- Deploy as a web app using Streamlit.

---
