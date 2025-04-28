# 📊 Customer Clustering — E-commerce Case Study

## Description

This project performs **customer clustering** for a British e-commerce business, using the **RFM** methodology (Recency, Frequency, Monetary) for customer segmentation.  
The objective is to group customers based on their purchasing behavior and support the development of **customer retention** and marketing strategies.

The notebook was developed as a practical case study for **DNC** students.

Additionally, the overall workflow follows the **CRISP-DM** (Cross Industry Standard Process for Data Mining) methodology, moving through Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment phases.

A complementary document was created to thoroughly describe the entire thought process and development of this case study, following the CRISP-DM stages.  
You can access it here:  
📄 [Full Case Documentation](https://drive.google.com/file/d/1qXT6kmwaR-K8rkMY-jwSrUfRqGHU6vDm/view?usp=sharing)

## 🔍 Methodology

The main stages of the project include:

1. **Business Understanding**
   - Definition of the business challenge: segment customers based on purchasing behavior patterns.

2. **Data Understanding**
   - Exploratory data analysis of transactions between December 2010 and December 2011.
   - Dataset source: [Ecommerce Data - Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data).

3. **Data Preparation**
   - Calculation of **RFM metrics** for each customer.
   - Treatment of outliers and inconsistent data.

4. **Modeling**
   - Application of clustering algorithms:
     - K-Means
     - Gaussian Mixture
     - DBSCAN
     - MeanShift
     - Agglomerative Clustering
   - Data scaling using `StandardScaler`.

5. **Evaluation**
   - Cluster quality assessment through:
     - **Silhouette Score**
     - **Davies-Bouldin Score**
     - **Calinski-Harabasz Score**

6. **Visualization**
   - Scatter plots, dendrograms, and elbow curve visualizations for cluster analysis.

## 📦 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy seaborn matplotlib plotly sidetable scikit-learn scipy yellowbrick
