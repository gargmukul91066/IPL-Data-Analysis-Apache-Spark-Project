# IPL-Data-Analysis-Apache-Spark-Project
<img width="885" height="562" alt="image" src="https://github.com/user-attachments/assets/a8c11d9e-c575-4103-99ea-f13281f4d981" />

This project focuses on performing an **end-to-end analysis of IPL data** using **Apache Spark** on **Databricks**. It demonstrates the process of setting up a distributed data processing environment, ingesting raw datasets, cleaning and transforming them, and generating insights through analytical queries and visualizations.

The goal is to show how large-scale sports datasets (IPL matches) can be processed efficiently to uncover meaningful patterns and trends using modern data engineering tools.

---

## 🛠️ Tech Stack

- **Apache Spark** (PySpark, Spark SQL)  
- **Databricks** (for distributed computing & visualization)  
- **Python**  
- **Pandas, Matplotlib, Seaborn** (optional for local visualization)  
- **Jupyter/Databricks Notebooks**

---

## 📂 Steps Involved

### 1️⃣ Data Cleaning
- Handled missing values and inconsistent records.
- Changed data types where required.
- Filtered valid deliveries only.
- Aggregated total and average runs scored in each match and inning.

### 2️⃣ Data Analysis
- Performed comprehensive analysis using Apache Spark and Databricks.
- Key metrics analyzed:
  - Player performance (batting averages, consistency)
  - Match statistics (runs per inning, win ratios)
  - Team trends across multiple IPL seasons
- Optimized Spark queries for efficiency on large datasets.
- Generated additional metrics like average scores, win rates, and player consistency.

### 3️⃣ Data Visualization
- Leveraged Databricks notebooks for data exploration and reporting.
- Created interactive dashboards and charts to visualize insights.

---

## 🔍 Key Insights

- **Team Performance After Winning the Toss:**  
  Chennai Super Kings (CSK) have the highest number of wins after winning the toss, followed by Mumbai Indians and Kolkata Knight Riders.  
  A noticeable correlation exists between winning the toss and winning the match.

- **Average Runs Scored by Batsmen in Winning Matches:**  
  Rashid Khan recorded the highest batting average in winning matches.

- **Top Venues for High Scores:**  
  OUTsurance Oval and Buffalo Park are the most batting-friendly venues.  
  Other high-scoring venues include Sheikh Zayed Stadium and Subrata Roy Sahara Stadium.

- **Most Frequent Dismissal Types:**  
  - Most common: Caught  
  - Others: Bowled, Run Out  
  - Rare: Obstructing the field, Retired hurt

- **Top vs. Lower Performing Teams After Winning Toss:**  
  - Top: CSK, MI, KKR convert toss wins into match wins most effectively  
  - Low: Pune Warriors, Kochi Tuskers Kerala have the least benefit from winning the toss

---

## 📸 Snapshots

*(<img width="1013" height="494" alt="image" src="https://github.com/user-attachments/assets/7defc33d-1609-44fd-823c-0ff0ca7f1c34" />
<img width="1010" height="494" alt="image" src="https://github.com/user-attachments/assets/6751c74d-ead6-41ff-ab6b-0aa854db30ec" />
<img width="1008" height="492" alt="image" src="https://github.com/user-attachments/assets/56565af7-2c6e-4cf8-88e3-7740d0a589ab" />
)*

---

## 📈 Learning Outcomes

- Hands-on experience with Apache Spark for distributed data processing.
- Understanding ETL pipelines: ingestion → cleaning → transformation → analysis.
- Gained insights into query optimization and handling large datasets.
- Built interactive dashboards and reports for stakeholders.




---
## 🔮 Future Improvements

- Automate data ingestion using **Airflow**.
- Store processed data in a **Data Lake** (e.g., Azure Data Lake / AWS S3).
- Extend the project to include **real-time streaming IPL data** with Kafka + Spark Streaming.
- Deploy dashboards with **Power BI / Tableau** for richer visualization.

---

## 👤 Author

**Mukul Garg**  
📧 [mukul91066gmail.com](mailto:mukul91066@gmail.com)  
