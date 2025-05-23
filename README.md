# Yelp Data Engineering and Sentiment Analysis Pipeline

This project demonstrates an end-to-end data pipeline using Yelp review and business data. It covers data extraction, transformation, sentiment enrichment, and SQL-based analysis.

---

## 🔄 End-to-End Workflow and File Descriptions

### 1. `yelp split files.ipynb`  
**Purpose:**  
Splits the large `yelp_academic_dataset_review.json` file (~5GB) into 10 smaller JSON files for easier processing and upload.  
**Stage:** Data Preparation

---

### 2. `Snowflake set up / UDF`  
**Purpose:**  
Creates Snowflake tables and transforms semi-structured JSON data (reviews and business info) into tabular format using the `FLATTEN` function and proper data types. 
Defines a Python UDF in Snowflake using the `TextBlob` library to perform sentiment analysis on review text and classify it as Positive, Neutral, or Negative.  
**Stage:** Data Ingestion & Transformation, Data Enrichment (NLP)

---

### 3. `SQL Analysis in Snowflake`  
**Purpose:**  
Defines a Python UDF in Snowflake using the `TextBlob` library to perform sentiment analysis on review text and classify it as Positive, Neutral, or Negative.  
**Stage:** Data Analysis & Reporting

---

## 🛠️ Technologies Used

- Python
- AWS S3
- Snowflake (SQL + Python UDF)
- TextBlob (Sentiment Analysis)

---

## 📬 Contact

**Tejesh Alaparthi**  
Email: alaparthitejesh8@gmail.com  
LinkedIn: [linkedin.com/in/tejesh-alaparthi](https://linkedin.com/in/tejesh-alaparthi)

