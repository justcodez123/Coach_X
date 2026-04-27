# Digital Marketing Analysis

This project provides a comprehensive analysis of digital marketing campaign performance using SQL and a detailed customer dataset. It focuses on identifying key drivers of conversion rates across different demographic segments and marketing channels.

## Project Overview

The primary goal of this analysis is to evaluate the effectiveness of various marketing channels (Social Media, Email, PPC, SEO, Referral) and understand customer behavior based on age, gender, and income levels.

## Dataset Description

The core of the analysis is based on `digital_marketing_campaign_dataset.csv`, which contains information such as:

- **Customer Demographics:** Age, Gender, Income.
- **Campaign Details:** Campaign Channel (PPC, SEO, Email, etc.), Campaign Type (Awareness, Retention, Conversion), Ad Spend.
- **Engagement Metrics:** Click-Through Rate (CTR), Conversion Rate, Website Visits, Pages Per Visit, Time On Site.
- **Interactions:** Social Shares, Email Opens, Email Clicks.
- **Customer Loyalty:** Previous Purchases, Loyalty Points.
- **Outcome:** Conversion (Success/Failure).

## SQL Analysis

The repository includes SQL scripts (`MARKETING_PARTIAL.sql` and `SQLQuery1.sql`) that perform the following operations:

### 1. Data Cleaning & Transformation
- Identifying null values in critical columns like Age, Income, and Gender.
- Categorizing customers into **Age Groups** (Young, Middle-Aged, Senior).
- Segmenting customers into **Income Groups** (Low, Middle, High Income).

### 2. Performance Metrics
- **Total Conversion Rate:** Calculated across the entire dataset (identified at approximately 87% in the sample analysis).
- **Channel Performance:** Evaluation of conversion rates by channel.
  - *Example Findings:* Referral and PPC often show higher conversion rates compared to other channels.
- **Demographic Insights:** Breakdown of conversions by Gender and Age Group to identify the most responsive segments.

### 3. Engagement Analysis
- Calculation of average metrics such as Pages Per Visit, Time On Site, and Website Visits.

## Files in the Repository

- `digital_marketing_campaign_dataset.csv`: The raw dataset used for analysis.
- `MARKETING_PARTIAL.sql`: SQL script focused on data cleaning, gender-wise conversion, and channel performance.
- `SQLQuery1.sql`: SQL script for advanced segmentation (Age and Income groups) and detailed engagement metrics.
- `digital_marketing.txt`: Basic project identification info.

## Key Insights (Sample)

| Campaign Channel | Conversion Rate (%) |
| :--- | :--- |
| Referral | 21.65% |
| PPC | 20.84% |
| SEO | 19.38% |
| Email | 19.32% |
| Social Media | 18.81% |

## How to Use

1. **Database Setup:** Import the `digital_marketing_campaign_dataset.csv` into your SQL environment (e.g., SQL Server, PostgreSQL).
2. **Execute Scripts:** Run the provided `.sql` files to replicate the analysis or use them as a template for further exploration.
3. **Analyze:** Use the results to optimize marketing spend and strategy based on high-performing channels and segments.

---
