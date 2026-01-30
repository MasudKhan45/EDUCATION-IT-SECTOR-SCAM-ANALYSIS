# EDUCATION-IT-SECTOR-SCAM-ANALYSIS

# 🛡️ Education & IT Sector Scam Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📊 Project Overview
This project analyzes **1,000+ reported scam incidents** within the Education and IT sectors between **2022 and 2026**.

The goal was to identify the most prevalent scam types, vulnerable platforms, and seasonal trends to create awareness and provide data-driven insights for safer digital navigation. The analysis reveals that job-related fraud is the most significant threat to students and professionals.

## 🖼️ Dashboard Preview
![Dashboard Preview](<img width="1125" height="643" alt="image" src="https://github.com/user-attachments/assets/fa8baee6-ca86-4565-a4e9-e32b31c0cda1" />
)

## 📂 Dataset Description
The dataset consists of **1,000 rows** of reported scam incidents with the following key attributes:
- **Date:** Incident timeline (2022-2026).
- **Platform:** The medium where the scam occurred (e.g., LinkedIn, WhatsApp, Review Sites).
- **Scam Type:** Categorized into *IT Job Scams*, *EdTech Fraud*, and *Course Selling Schemes*.
- **Scam Category:** Specific methods used (e.g., "Fake Offer Letter", "Refund Denial").
- **Description:** Detailed text of the incident.

## 🛠️ Tech Stack & Workflow
- **Data Source:** Custom CSV Dataset (`Education_IT_Scams_Dataset.csv`)
- **ETL & Data Cleaning:** - **Data Merging:** Consolidated fragmented categories (e.g., merged "IT Job", "IT Job/Internship", and "IT Job Scam" into a single **"IT Job Scam"** category) for accurate aggregation.
  - **Time Series Extraction:** Extracted **Year** and **Month** using Power Query to analyze seasonal trends.
  - **Data Type Casting:** Fixed aggregation errors by converting "Serial_No" from Sum to Count.
- **Visualization:** Microsoft Power BI (Interactive Dashboard).

## 🔍 Key Insights
1. **IT Job Scams are the Dominant Threat:** - After data cleaning and categorization, **IT Job-related scams** (including fake offers and internships) account for nearly **48%** of all reported incidents, making them the single largest threat category.
   
2. **Platform Vulnerability:** - Reports indicate that **"Legal Platforms"** and **"Company Review Sites"** are frequently cited in scam reports (~15% combined), likely used by scammers to feign legitimacy or post fake reviews.
   
3. **Seasonal Trends:** - **January** sees the highest volume of reported scams (109 incidents), suggesting scammers target job seekers heavily at the start of the year when "New Year, New Job" searches peak.

## 📈 Dashboard Features
The interactive Power BI dashboard includes:
- **Donut Chart:** Visualizes the distribution of major scam types (IT Job vs. EdTech vs. Education System).
- **Line Chart:** Tracks scam trends over 4 years to identify spikes and seasonality.
- **Clustered Bar Chart:** Breaks down scam frequency by platform.
- **Matrix View:** A heatmap cross-referencing Scam Types with Platforms to identify high-risk combinations.
- **Key Metrics Cards:** Displays "Total Scams," "Top Category," and "Date Range" for instant context.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/MasudKhan45/EDUCATION-IT-SECTOR-SCAM-ANALYSIS]
