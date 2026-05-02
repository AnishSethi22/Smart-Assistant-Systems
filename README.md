# 🤖 Smart Assistant System for Intent Recognition

---

## 📌 Project Overview
This project focuses on building a Smart Assistant System using the CLINC150 dataset. It analyzes user queries to understand different intents and improve response accuracy in conversational AI systems.

---

## 🎯 Problem Statement
How can a smart assistant accurately identify user intent when the same request can be expressed in multiple ways?

---

## 🚀 Objectives
- Analyze user query patterns  
- Understand intent distribution  
- Improve intent recognition accuracy  
- Detect and handle outliers  
- Prepare data for machine learning models  

---

## 📂 Dataset
Dataset Used: **CLINC150 Dataset**

### Key Features:
- ~23,700 user queries  
- 150 intent categories  
- 10 domains  

### Columns:
- text → user query  
- intent → intent label  
- domain → category  
- split → train/test/validation  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔄 Project Workflow

### 1. Data Collection
- Imported dataset from CSV  

### 2. Data Cleaning
- Removed missing values  
- Removed duplicates  
- Converted data types  
- Cleaned text  

### 3. Data Analysis
- Mean query length analysis  
- Domain distribution  
- Statistical analysis  
- Z-score normalization  
- IQR outlier detection  

### 4. Data Visualization

#### 📈 Matplotlib
- Query trends  
- Top intents  
- Histogram  

#### 📊 Seaborn
- Countplot  
- Heatmap  
- Violin plot  

---

## 📊 Key Insights
- Uneven intent distribution  
- Strong correlation between query length and word count  
- Outliers affect analysis  
- Some intents dominate queries  

---

## 📌 Results
- Clean dataset improves accuracy  
- Clear query patterns identified  
- Ready for ML model training  

---

## 🔮 Future Scope
- Machine learning models  
- Deep learning (BERT, NLP)  
- Multilingual support  

---
## 👥 Team Members
- **Anish Sethi** (RA2311003010365)  
- **Syed Asifa** (RA2311003010364)  
- **Kritak Prasad** (RA2311003010367)  

---
## ▶️ How to Run

```bash
git clone <your-repo-link>
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
