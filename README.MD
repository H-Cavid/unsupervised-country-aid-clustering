# 🌍 WHO Country Development Clustering Project

This project analyzes health and economic indicators to identify countries most in need of aid. Using unsupervised learning techniques like KMeans and hierarchical clustering, it supports the World Health Organization (WHO) in prioritizing how to distribute $50 million in funds.

✅ *Project developed as part of the "Machine Learning and Data Analysis" module during my Data Science studies.*

---

## 🔍 Objectives

- Analyze socio-economic indicators of countries  
- Identify countries with high need based on:
  - Child mortality  
  - GDP per capita  
  - Income  
  - Health spending  
- Group countries using clustering techniques  
- Recommend the top 10 countries most in need of WHO aid

---

## 📊 Dataset

- Source: [Kaggle – Country Data Clustering](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)
- Raw file: `data/Country-data.csv`

---

## 🛠️ Technologies Used

- Python 3.11.8 
- pandas  
- seaborn  
- matplotlib  
- plotly  
- scikit-learn  
- Jupyter Notebook

---
## 🐍 Python Version

This project requires **Python 3.11.x** due to compatibility with the `yellowbrick` library, which depends on the deprecated `distutils` module that is no longer available in Python 3.12 and above.

> ✅ Please ensure you are using Python 3.11 when creating your virtual environment.

## 🔧 Techniques Used

- Exploratory Data Analysis (EDA)  
- StandardScaler, MinMaxScaler  
- KMeans & Hierarchical Clustering (HAC)  
- PCA (Principal Component Analysis)  
- Plotting: Matplotlib, Seaborn, Plotly  

---

## 🗂️ Project Structure

```
WHO-Country-Clustering/
    │
    ├── data/ → Country-data.csv (input dataset)
    ├── notebooks/ → experiments.ipynb (main analysis notebook)
    ├── requirements.txt → Python dependencies
    ├── README.md → This file
    ├── .gitignore → To ignore unnecessary files
    └── env/ → Virtual environment (not pushed to GitHub)
```
---

## 📈 Visualizations

- Histograms and boxplots of feature distributions  
- Choropleth maps for global comparisons  
- Bar charts for extreme values (child mortality, exports, etc.)  
- Dendrogram (hierarchical clustering)  
- Silhouette and elbow plots (for KMeans cluster evaluation)  
- PCA visualization of clusters

---

## 📄 Results

- Identified 4 country clusters using both KMeans and HAC  
- Selected the cluster with **high child mortality and low GDP**  
- Top 10 countries needing aid were listed based on this cluster

---

## ▶️ How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/WHO-Country-Clustering.git
cd WHO-Country-Clustering

# Create virtual environment
python -m venv env
source env/bin/activate  # Or use `env\Scripts\activate` on Windows

# Install required libraries
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/experiments.ipynb
```


## 📜 License

This project is licensed under **CC BY-NC-ND 4.0**.

- You **can** view and share the project with proper credit.  
- You **cannot** use it for commercial purposes or modify/reuse it as your own.

---

## 👤 Author

**Javid Hasanov**  
Master's student in Data Science at FH Kiel
  
[LinkedIn](https://www.linkedin.com/in/javidhasanov-tech) • [GitHub](https://github.com/H-Cavid)

