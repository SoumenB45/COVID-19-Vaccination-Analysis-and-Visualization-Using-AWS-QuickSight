# 🦠 COVID-19 Vaccination Analysis and Visualization Using AWS QuickSight

## 📌 Key Objectives

- **Data Collection**: Acquire datasets from reliable sources  
- **Data Processing**: Clean and preprocess the data for analysis  
- **Data Analysis**: Identify different patterns and trends  
- **Data Visualization**: Develop interactive dashboards using **AWS QuickSight**

---

## 📂 Data Source

- [Kaggle - COVID-19 Vaccination Dataset](https://www.kaggle.com/)

---

## ☁️ Data Storage

- **Amazon S3**:  
  - Store raw CSV data securely  
  - Store processed data for downstream tasks  

- **Amazon RDS (PostgreSQL)**:  
  - Store structured and cleaned data  
  - Enable efficient querying and analytics  

---

## 🔄 Data Processing

- **AWS Glue**:  
  - Perform ETL (Extract, Transform, Load) operations  
  - Clean and transform the dataset for analysis  

### Example Transformations
- Convert date fields to ISO format  
- Handle missing or null values appropriately  

---

## 📊 Data Visualization

- **Amazon QuickSight**:  
  - Create interactive dashboards and visualizations  
  - Enable drill-down analytics and filtering features  

### Sample Visuals:
- Total vaccinations over time by country  
- Vaccination rate by population segment  

---

## 🔐 Security and Monitoring

- **AWS IAM (Identity and Access Management)**:  
  - Control access to AWS services and resources securely  

- **AWS CloudWatch**:  
  - Monitor AWS Glue jobs and QuickSight dashboards  
  - Track performance metrics and detect errors  

---

## 🧭 Solution Architecture

### 1️⃣ Data Ingestion
- Download vaccination datasets from Kaggle  
- Upload raw CSV files to **Amazon S3** (secured bucket)  

### 2️⃣ ETL with AWS Glue
- Use **Glue Crawlers** to catalog datasets  
- Develop **ETL Jobs** for:
  - Data cleaning  
  - Data transformation  
  - Loading into **Amazon RDS**

### 3️⃣ Data Storage
- Store cleaned and structured data in **Amazon RDS**

### 4️⃣ Visualization in QuickSight
- Connect **Amazon QuickSight** to:
  - **Amazon RDS** (PostgreSQL)  
  - Or **Amazon S3** using **Athena**  
- Build insightful dashboards with:
  - Country-wise trends  
  - Population-based vaccination analytics  

---

## ✅ Tools and Technologies

| Category        | Tools & Services                |
|----------------|----------------------------------|
| Data Source     | Kaggle                          |
| Storage         | Amazon S3, Amazon RDS           |
| ETL             | AWS Glue                        |
| Visualization   | Amazon QuickSight               |
| Monitoring      | AWS CloudWatch                  |
| Security        | AWS IAM                         |

---

## 📌 Author

**Soumen Baidya**  
[LinkedIn](https://www.linkedin.com/in/soumen-baidya/) • [GitHub](https://github.com/SoumenB45) • Email: baidyasoumen50@gmail.com  
