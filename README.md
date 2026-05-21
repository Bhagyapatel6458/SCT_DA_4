# Task 04 - Business Insights Report (EDA)

## Overview
Exploratory Data Analysis (EDA) performed on a Marketing Campaign Dataset to identify which channels deliver the best ROI and recommend budget allocation.

## Objective
Instead of building a Machine Learning model, the focus is on the "Why." Clean the data, visualize the funnel, and write a 1-page summary report recommending which marketing channels should receive more budget based on ROI.

## Dataset
- Total Campaigns: 1000
- Channels: Email, Social Media, SEO, Paid Search, Referral
- Features: Impressions, Clicks, Leads, Conversions, Spend, Revenue

## Steps Performed
1. Created and loaded the marketing campaign dataset
2. Cleaned the data (removed nulls and duplicates)
3. Added calculated metrics (CTR, Conversion Rate, ROI)
4. Explored data by channel
5. Visualized the marketing funnel
6. Analyzed ROI by channel
7. Written 1-page business summary report

## Key Findings
- Best ROI Channel: Email
- Best Conversion Rate: Referral
- Worst ROI Channel: Social Media

## Recommendations
- ✅ INCREASE budget for Email and Referral (High ROI)
- ⚠️ MAINTAIN budget for SEO and Paid Search (Average ROI)
- ❌ REDUCE budget for Social Media (Low ROI, High Spend)

## Files
| File | Description |
|---|---|
| `task04_marketing_eda.ipynb` | Main Jupyter Notebook |
| `marketing_campaign.csv` | Dataset used for analysis |
| `funnel_chart.png` | Marketing Funnel Chart |
| `roi_chart.png` | ROI by Channel Chart |

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Author
SkillCraft Technology - Data Analytics Internship
Task 04
