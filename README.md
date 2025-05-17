# BigData-AI-COVID-19-Trend-Predictor

This project uses Big Data technologies and AI to analyze and predict COVID-19 trends. It leverages data ingestion with Kafka, data storage with HDFS, real-time processing with Spark Streaming, and AI modeling to forecast pandemic progression. A Streamlit dashboard provides an interactive visualization of predictions.

---

## Project Structure

- `data/`  
  Contains the COVID-19 datasets used for training and evaluation.

- `hdfs/`  
  Scripts for handling data storage and retrieval on HDFS.

- `kafka/`  
  Producer and consumer scripts for streaming COVID-19 data.

- `models/`  
  AI models and associated metadata/metrics.

- `spark-streaming/`  
  Spark Streaming jobs for real-time prediction.

- `streamlit/`  
  Dashboard to visualize COVID-19 trends and model predictions.

---

## Technologies Used

- Apache Kafka  
- Hadoop HDFS  
- Apache Spark Streaming  
- Python (PySpark, Kafka-python, Streamlit)  
- Machine Learning models (custom pandemic prediction)

---

## How to Run

1. Setup Kafka and HDFS clusters.  
2. Start Kafka producers and consumers.  
3. Run Spark Streaming jobs to process data and generate predictions.  
4. Launch Streamlit dashboard to monitor results:
   streamlit run streamlit/dashboard.py
