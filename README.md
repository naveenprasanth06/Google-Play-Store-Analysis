# 📊 Google Play Store Analysis — 23CS103 Data Science Case Study

## 🧠 Project Overview
This project presents a **complete end-to-end data analysis workflow** focused on the **Google Play Store ecosystem**.  
It involves **data collection (via web scraping)**, **data cleaning and transformation**, and **visual analytics** using **Power BI** and **Tableau**.

Developed as part of the **23CS103 – Data Science Project**, this case study highlights the ability to turn **unstructured web data into actionable business insights**.

---

## 🎯 Objectives

- 🔹 Collect real-time data from Google Play Store (multiple categories).
- 🔹 Clean, preprocess, and normalize datasets for analytics.
- 🔹 Identify patterns in **ratings, pricing, and availability**.
- 🔹 Visualize insights using **interactive dashboards**.
- 🔹 Provide **data-driven recommendations** for decision-making.

---

## 🌐 Data Source

Data was obtained from **publicly available Play Store pages and demo datasets**.  
Each record includes the following fields:

| Field | Description |
|--------|--------------|
| **Title / Name** | Application title |
| **Price / Value** | App cost or price in INR |
| **Availability / Status** | Free / Paid / Not Available |
| **Ratings / Reviews** | Average user rating and review count |
| **Category / Type** | Genre of the app (Games, Tools, Education, etc.) |
| **Additional Info** | Optional metadata like installs, version, or size |

---

## 🧩 Repository Structure

```bash
Google-PlayStore-Analysis/
│
├── Google Play Store Analysis.ipynb     # Jupyter Notebook (scraping + cleaning + EDA)
├── cleaned_data.csv                      # Processed dataset
├── Google Play Store Analysis.pdf        # Final report (insights + recommendations)
├── dashboards/
│   ├── GooglePlay_Analysis.pbix          # Power BI Dashboard
│   └── GooglePlay_Analysis.twbx          # Tableau Dashboard
└── README.md                             # Project documentation
