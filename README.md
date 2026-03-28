# 🚦 Traffic Flow Prediction on PEMS03 Dataset

## 📌 Overview
Predicting highway traffic patterns using large-scale data engineering and machine learning pipelines built on PySpark, HDFS, and Hive.

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| PySpark | Distributed data processing |
| HDFS | Large-scale storage |
| Hive | SQL querying on big data |
| Python | Modeling & visualization |
| Matplotlib / Seaborn | Data visualization |

## 📊 Results
| Model | Metric | Score |
|-------|--------|-------|
| Logistic Regression | Accuracy | **99.45%** |
| Random Forest | R² Score | **88.7%** |

## ⚡ Key Highlights
- Processed large-scale PEMS03 highway traffic data — achieved **60% faster** data handling with PySpark
- Built and compared two ML models for traffic flow prediction
- Feature engineering pipeline designed for scalability
- Visual insights generated with Matplotlib and Seaborn

## 📁 Project Structure
- `Project_Spark.ipynb` — Main notebook with full pipeline: data ingestion → processing → modeling → visualization

## 🚀 How to Run
1. Clone this repository
2. Ensure PySpark and Hadoop are configured in your environment
3. Open `Project_Spark.ipynb` in Jupyter
4. Run all cells sequentially
