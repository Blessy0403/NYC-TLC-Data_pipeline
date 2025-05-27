# NYC-TLC-Data_pipeline
Scalable Docker-based ETL pipeline for analyzing NYC TLC Taxi data using Redis, PostgreSQL, and Tableau – includes real-time processing and insightful traffic analytics.

nyc-tlc-data-pipeline

Scalable Docker-based ETL pipeline for analyzing NYC TLC Taxi data using Redis, PostgreSQL, and Tableau – includes real-time processing and insightful traffic analytics.
🚖 NYC TLC Data Engineering Pipeline

📘 Project Title: Customer and Traffic Insights with TLC Data

🎓 Course: Data Engineering
📌 Overview

This project builds a scalable end-to-end ETL pipeline to analyze New York City Taxi (TLC) data. It combines Dockerized services, Redis for caching, PostgreSQL for structured storage, and Tableau for data visualization, enabling actionable insights into urban mobility, customer behavior, and payment trends.

🛠️ Tools & Technologies

* Docker 🐳
* Redis ⚡ (for real-time caching)
* PostgreSQL 🐘 (with PGAdmin)
* Tableau 📊 (for visualization)
* Python (Producer & Consumer scripts)
* NYC TLC Taxi Data (Yellow Taxi - 2024, 100k+ records)

🧱 Pipeline Architecture

Excel Preprocessing ➝ Redis Producer ➝ Consumer ➝ PostgreSQL ➝ Tableau
Components (Docker Containers):
* Producer
* Consumer
* Redis Server
* PostgreSQL
* PGAdmin

🧪 Dataset

Source: NYC TLC Trip Data Size: 15 MB (100,000 records) Fields (19 total):
* Pickup & Drop-off Timestamps
* Trip Distance, Fare, Taxes, Tip
* Payment Type, Passenger Count
* Latitude/Longitude for pickups & drop-offs

⚙️ Setup Instructions

1. Clone the repository
2. Modify your .env or .yml file for ports and credentials
3. Run:docker compose build
4. docker compose up
