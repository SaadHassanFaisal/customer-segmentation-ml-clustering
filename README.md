# 🛍️ Behavioral Segmentation of Retail Customers using Clustering

🚀 **Overview**  
This project develops an **unsupervised machine learning pipeline** to segment retail customers based on purchasing behavior.  
By applying clustering algorithms on transactional data, customers are grouped into **actionable segments** that support:  
- Targeted marketing campaigns  
- Customer retention strategies  
- Revenue growth initiatives  

The solution includes:  
- A **reproducible end-to-end pipeline** in Jupyter Notebooks  
- **Multiple clustering approaches** with rigorous validation  
- A **Flask-based API** for real-time customer segmentation  

---

## 📂 Project Workflow

1. **Data Preprocessing**  
   - Handled missing values and outliers  
   - Normalized features using MinMaxScaler  
   - Encoded categorical attributes (Label Encoding)  

2. **Feature Engineering**  
   - Derived **RFM metrics** (Recency, Frequency, Monetary value)  
   - Created customer-level aggregated dataset  

3. **Clustering & Evaluation**  
   - Algorithms tested: K-Means, MiniBatch K-Means, Gaussian Mixture Models, DBSCAN, Hierarchical, Birch, Spectral  
   - Validation with **Silhouette Score**, **Davies–Bouldin Index**, and **Calinski–Harabasz Index**  
   - Dimensionality reduction with PCA for visualization and interpretability  

4. **Deployment**  
   - Trained models serialized with **Joblib**  
   - Flask API built for real-time prediction of customer segments  
   - Optional **ngrok integration** for remote accessibility  

---

## 🎯 Key Features
- End-to-end **behavioral segmentation pipeline**  
- **Multiple clustering algorithms** for robustness and comparison  
- Clean **cluster profiling** with interpretable insights  
- **Deployment-ready Flask app** for business integration  

---

## 📊 Results & Insights
- Optimal number of clusters identified using elbow method + validation metrics  
- Segmentation revealed **clear behavioral patterns**, e.g.:  
  - High-value loyal customers  
  - Price-sensitive occasional buyers  
  - One-time or at-risk customers  
- Visualizations confirm meaningful separation of clusters in reduced dimensions  

---

## 🛠️ Tech Stack
- **Languages**: Python, Html, CSS, JavaScript
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn  
- **Frameworks**: Jupyter Notebook  
- **Deployment**: Flask API + ngrok 

---

## 📈 Business Value
This project demonstrates how unsupervised learning can transform raw retail transactions into **strategic insights**:  
- 📌 **Marketing**: Launch targeted campaigns per segment  
- 📌 **Customer Retention**: Detect churn-prone groups early  
- 📌 **Revenue Optimization**: Prioritize high-value clusters  
- 📌 **Personalization**: Deliver tailored promotions and experiences  

---

## 🤝 Contributors
- 👨‍💻 **Saad Hassan Faisal** – Machine Learning & Software Engineer  
- 👨‍💻 **Saadullah** – Collaborator  

---

## ⚖️ License
This project is licensed under the MIT License.  
