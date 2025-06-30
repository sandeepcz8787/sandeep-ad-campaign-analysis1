📊 Facebook Ad Campaign Funnel Analysis – by Sandeep Chavhan
🔍 Overview
This project analyzes a real-world Facebook ad campaign dataset to uncover trends in user engagement and campaign performance. I used Python, SQL concepts, and Power BI to calculate and visualize key advertising metrics like CTR, CPC, Conversion Rate, and ROAS.

🎯 Objectives
Understand user behavior across different age and gender groups

Identify high- and low-performing ad segments

Recommend actionable strategies to improve campaign ROI

🛠️ Tools & Technologies
Python: Pandas, Matplotlib, Seaborn

Power BI: Interactive dashboards and segment analysis

SQL logic: For calculating metrics like CTR and conversions

📈 Key Metrics Calculated
Click-Through Rate (CTR) = Clicks / Impressions

Cost Per Click (CPC) = Spent / Clicks

Conversion Rate = Conversions / Clicks

ROAS (assumed) = Revenue / Spend (using assumed revenue per conversion)

💡 Insights
Users aged 30–34 had the highest CTR across both genders

Conversion rate was lower for higher spend segments, indicating optimization issues

Suggested retargeting younger users with new creatives to reduce CPC and improve ROAS

📊 Power BI Dashboard
The dashboard includes:

Campaign performance summary

CTR and conversion trends by demographic

Ad spend efficiency insights



![Total-Conversion-Approved-Conversion-and-Impressions-by-Day-Plot](https://github.com/user-attachments/assets/79c40978-5c97-45b9-b68f-ef3d2008f24a)

![Approved-Conversion-Amount-SPent-and-Clicks-by-Age-Range-and-Campaign-Range-Plot](https://github.com/user-attachments/assets/c9dc084d-937e-4d36-a738-7189e9fd1b09)

![Total-Conversion-Approved-Conversion-and-Clicks-by-Day-Plot](https://github.com/user-attachments/assets/c0e6b72e-0f62-40a1-9a6f-6c3119c34f5f)

✅ Outcome
This project simulates a real-world campaign optimization task and shows my ability to:

Work with ad data

Build actionable insights

Present them clearly using business intelligence tools

## About the dataset

The following are the features we'll use to predict our target variable (approved conversion).
The data used in this project is from an anonymous organisation’s social media ad campaign.
There are 15 attributes:
<details><summary><b>Click to know more </b></summary>   

1. **ad_id**: an unique ID for each ad.

2. **reporting_start**: the start of the reporting of the advertisement's reach.

3. **reporting_end**: the start of the reporting of the advertisement's reach.

4. **campaign_id**: an ID associated with each ad campaign of XYZ company.

5. **fb_campaign_id**: an ID associated with how Facebook tracks each campaign.

6. **age**: age of the person to whom the ad is shown.

7. **gender**: gender of the person to whim the add is shown

8. **interest(1,2,3)**: a code specifying the category to which the person’s interest belongs (interests are as mentioned in the person’s Facebook public profile).

9. **impressions**: the number of times the ad was shown.

10. **clicks**: number of clicks on for that ad.

11. **spent**: Amount paid by company xyz to Facebook, to show that ad.

12. **total_conversion**: Total number of people who enquired about the product after seeing the ad.

13. **approved_conversion**: Total number of people who bought the product after seeing the ad.

</details>

  >Note: Names of the columns were changed while transforming the data in Power BI.

## Sources

- Dataset: [https://www.kaggle.com/madislemsalu/facebook-ad-campaign](https://www.kaggle.com/madislemsalu/facebook-ad-campaign) Kaggle 

- Dataset factors explanation: [https://www.kaggle.com/chrisbow/an-introduction-to-facebook-ad-analysis-using-r/data](https://www.kaggle.com/chrisbow/an-introduction-to-facebook-ad-analysis-using-r/data)
Kaggle
