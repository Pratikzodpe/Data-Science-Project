# 🌍 Cluster Analysis on Global Development Measurement Dataset

This project focuses on clustering countries based on various global development and economic indicators. It involves data preprocessing, dimensionality reduction, clustering, evaluation, and deployment using Streamlit.

## 📊 Features of the Dataset
The dataset includes features such as:
- GDP
- Birth Rate
- CO2 Emissions
- Healthcare Expenditure
- Internet Usage
- Life Expectancy
- Ease of Doing Business
- And many more...

## 🔧 Project Workflow

1. **Data Cleaning & Preprocessing**  
   - Handled missing values using mean, median, and mode.  
   - Detected outliers using boxplots and Isolation Forest.

2. **Feature Engineering**  
   - Applied dimensionality reduction techniques like PCA, t-SNE, and UMAP.  
   - Chose UMAP for best separation of clusters.

3. **Clustering Models Used**  
   - K-Means Clustering  
   - Hierarchical Clustering  
   - DBSCAN  
   - Determined optimal clusters using the elbow method and silhouette score.

4. **Model Optimization**  
   - Used GridSearchCV to find the best parameters.

5. **Deployment**  
   - Deployed the final clustering model using **Streamlit** for a user-friendly interface.

## 🚀 Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- UMAP, t-SNE, PCA  
- Matplotlib, Seaborn  
- Streamlit

## ✅ Outcome
This project helped in understanding how different countries group together based on economic and development metrics. It improved my hands-on skills in data preprocessing, clustering algorithms, model evaluation, and deployment.
