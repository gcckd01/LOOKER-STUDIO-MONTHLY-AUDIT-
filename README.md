# LOOKER-STUDIO-MONTHLY-AUDIT
An end-to-end retail data analytics project identifying sales funnel drop-offs, TAT bottlenecks, and customer sentiment (NPS) using Python, Google Sheets, and Looker Studio
# 📊 Retail Lead Conversion & Operational Efficiency Analysis

## 🎯 Project Objective
The goal of this project is to optimize the sales funnel for a retail company by identifying drop-off points, analyzing turnaround time (TAT) bottlenecks, and evaluating customer sentiment (NPS) across four major store locations (Bangalore, Chennai, Delhi, Mumbai).

**Live Interactive Dashboard:** https://lookerstudio.google.com/reporting/e2d6829b-30b5-4f32-835f-587662ddfd88

## 🛠️ Tools Used
* **Data Cleaning & Feature Engineering:** Google Sheets (Formulas, Data Validation)
* **Exploratory Data Analysis (EDA):** Python (Pandas) / Google Sheets Pivot Tables
* **Data Visualization:** Looker Studio

## 🧠 Key Insights Discovered
1. **The Conversion Bottleneck:** While the overall conversion rate (Lead to Delivery) is 72.9%, there is an **18.8% drop-off** immediately at the Pre-Booking stage. Once a lead pre-books, the conversion to delivery is nearly 100%.
2. **Critical Customer Sentiment (NPS):** The overall Net Promoter Score (NPS) is alarmingly low (**-53 average**), with Bangalore performing the worst (-58). This indicates severe post-sales service issues despite efficient delivery speeds.
3. **Lost Revenue Analysis:** 8.3% of "Delivered" orders were ultimately marked as Cancelled (Returns). The primary reasons for lost leads overall were "Financing Issues" and "Price", suggesting a need for better consumer credit partnerships.

## 📂 Project Structure
1. **Data Preprocessing:** Standardized date formats, handled missing values in TAT columns, and created a dynamic `Final Status` column to separate pipeline leads from actual cancellations/returns.
2. **Feature Engineering:** * Calculated custom **NPS Categories** (Promoter, Passive, Detractor) based on 1-10 customer ratings.
   * Calculated **Stage-to-Stage Drop-off Rates**.
3. **Dashboard Design:** Built an interactive Looker Studio dashboard featuring dynamic cross-filtering by Store and Lead Type.

## 📸 Dashboard Preview
  
<img width="469" height="355" alt="image" src="https://github.com/user-attachments/assets/c1d561bb-da26-46d4-a8ba-b1e5e23afd6f" />

