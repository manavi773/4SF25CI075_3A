# Spotify Reviews Data Analysis – Milestone 1 (CIE)

## Project Overview
This repository contains the exploratory data analysis and data preprocessing performed on a dataset of **61,594 Spotify app reviews**. The goal of this analysis is to evaluate user sentiment across star ratings, understand developer engagement rates, and prepare a clean dataset for further modeling.

---

## Repository Details
* **Student USN / Section:** 4SF25CI075_3A
* **Project Milestone:** Milestone 1 – Continuous Internal Evaluation (CIE)
* **Dataset Size:** 61,594 records

---

## Key Features & Workflow

### 1. Data Preprocessing & Cleaning
* **Date & Time Feature Extraction:** Parsed review timestamps into structured temporal features (Year, Month, Day, Hour).
* **Categorical Standardization:** Standardized the `Reply` field into distinct categories (`Reply` vs. `No Reply`) to prevent label fragmentation during plotting.
* **Sorting & Consistency:** Cleaned and sorted numerical rating distributions (1–5 stars) to guarantee proper chronological representation across all charts.

### 2. Visualization & Insights
* **Rating Distribution:** Horizontal bar plots, sorted bar plots, and color-coded pie charts illustrating the distribution of star ratings across 1 to 5 stars.
* **Developer Response Rate:** Visualized developer engagement ratios to highlight the proportion of user reviews receiving direct replies.
* **Metric Correlations:** Explored relationships between community engagement indicators (e.g., `Total_thumbsup`) and corresponding star ratings.

---

## File Structure