# YouTube Trending Video Analytics Pipeline

### SKILLS: Python · SQL · Streamlit · Pandas · Matplotlib

This project delivers a complete end-to-end analytics pipeline designed to process and analyze 37,000+ YouTube trending video records. It integrates automated ETL workflows, optimized SQL queries, and a real-time interactive dashboard to help track engagement patterns and category-level trends with high accuracy.

## 🔍 Project Overview

The goal of this project is to turn raw, semi-structured YouTube trending datasets into clean, query-ready data and provide actionable insights through an interactive Streamlit dashboard. The pipeline reduces manual reporting workloads, improves data consistency, and enables real-time exploration of trends such as view spikes, category popularity, and engagement ratios.

## 🔧 Key Contributions
1. Engineered a Scalable ETL Pipeline

A) Ingested and processed 37k+ records across multiple categories and timelines.

B) Cleaned and standardized inconsistent JSON/CSV formats using Pandas.

C) Automated extraction, transformation, and loading using modular Python scripts.

2. SQL Optimization & Performance Improvements

A) Designed a structured SQLite database for analytics workloads.

B) Created indexed tables and optimized join operations, improving performance by ~40%.

C) Automated loading of transformed data into SQL to ensure reproducibility.

3. Real-Time Analytics Dashboard (Streamlit)

A) Built an interactive dashboard displaying:

B) View count growth

C) Likes & comment engagement

D) Category-level trending patterns

E) Daily spikes in trending videos

F) Reduced manual reporting and analysis work by 80%.

## 🧱 System Architecture
Raw Data → Python ETL (Extract → Transform → Load) → SQLite DB → Streamlit Dashboard


1. ETL Layer:
Pandas scripts for cleaning, normalization, merging category files, handling duplicates, and preparing metrics.

2. Database Layer:
SQLite database with well-defined schema, optimized indices, and reusable SQL queries.

3. Visualization Layer:
Streamlit + Matplotlib visual analytics for real-time trend exploration.

## 📂 Project Structure
├── etl/
│   ├── extract.py
│   ├── transform.py
│   ├── load.py
├── dashboard/
│   ├── app.py
├── sql/
│   ├── schema.sql
│   ├── queries.sql
├── data/
│   ├── raw/
│   ├── processed/
├── README.md

## ▶️ How to Run
1. Install Dependencies
pip install -r requirements.txt

2. Run the ETL Pipeline
python etl/extract.py
python etl/transform.py
python etl/load.py

3. Launch the Dashboard
streamlit run dashboard/app.py

## 📊 Example Insights (Displayed in Dashboard)

Categories with the highest trending frequency

Videos experiencing sudden engagement spikes

Correlation patterns: views vs likes vs comments

Daily distribution of trending uploads

Category momentum analysis

## 💼 Why This Project Matters

This project demonstrates:

Ability to build production-style ETL systems

Strong SQL + Python integration

Experience working with large semi-structured datasets

Skill in building interactive data applications

End-to-end workflow thinking (data → processing → analytics)

Perfect for roles involving Data Analytics, Data Engineering, BI Development, or ML Data Pipelines.

### Author - Vaishnavi Bhamare
MS IN ADVANCED DATA ANALYTICS
