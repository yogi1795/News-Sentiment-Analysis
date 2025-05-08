# - 📰 Real-Time Sentiment Analysis from News Data Using Microsoft Fabric
In this project, I designed and implemented a complete **end-to-end data pipeline using Microsoft Fabric**, combining the strengths of data engineering, data science, and business intelligence—all in a single, unified environment.

### 🔧 Project Overview
The objective was to extract real-time news data, analyze the sentiment of each article, and present the results through an interactive Power BI dashboard. The entire process was orchestrated within Microsoft Fabric, showcasing its capabilities as a modern, cloud-first data platform.

### 🔄 Data Engineering: Ingesting and Transforming News Data
- The pipeline began by ingesting **raw JSON news data**.

- Using **PySpark in a Spark notebook**, I parsed and transformed the JSON into structured tabular format.

- I implemented **upsert logic** (merge if exists, insert if new) to efficiently store this data in a **Delta Lake** table within Fabric’s Lakehouse.

- The transformation included flattening nested structures and standardizing timestamps for downstream processing.

### 🧠 Data Science: Sentiment Analysis with Microsoft Cognitive Services
- I integrated Spark built-in capabilities to run sentiment analysis on the news articles.

- Each article was classified as **positive**, **neutral**, or **negative**, with a confidence score attached.

- These enriched insights were appended to the structured data and stored back in the Lakehouse for reporting.

### 📊 Business Intelligence: Building a Semantic Model and Power BI Dashboard
- I built a **semantic model** in Fabric to enable business-friendly reporting.

- Using Power BI, I created an interactive dashboard that visualizes:

- - Volume of news articles over time

- - Sentiment distribution (overall and by category)

- - Trends and spikes in public sentiment

- The report enables end-users to drill down by time, keyword, or sentiment category.

### 👨‍💻 My Role in the Project
Throughout the project, I worked across disciplines:

- As a Data Engineer: I built the data pipeline, handled schema management, and optimized data storage using Delta Lake.

- As a Data Scientist: I applied sentiment analysis and evaluated AI model outputs.

- As a Data Analyst: I built compelling visualizations that make complex insights easy to understand.

### 🚀 Why Microsoft Fabric?
This project reinforced my belief in the power and versatility of Microsoft Fabric. It allowed me to perform the full spectrum of data tasks—from ingestion and transformation to AI enrichment and reporting—without switching platforms.

Fabric’s native integration across Lakehouse, Notebooks, Power BI, and AI services makes it a game-changer for modern data teams
