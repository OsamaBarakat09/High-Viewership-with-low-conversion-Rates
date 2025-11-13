# 📉 High Viewership with Low Conversion Rates

Understanding why a marketing campaign or social media content can attract a large audience but fail to convert that attention into meaningful actions — such as purchases, sign-ups, or engagement.

This project applies data science and marketing analytics to identify the underlying causes behind low conversion rates despite strong viewership metrics, using real-world data and advanced analytical techniques.
## 🚨 Problem Statement

Modern marketing campaigns often generate significant traffic and engagement metrics — high impressions, clicks, or video views — but still fail to achieve desired conversion goals.

This project investigates *why high viewership does not always translate into high conversions*, aiming to:
- Identify audience behavior patterns leading to drop-offs.
- Analyze the effectiveness of marketing channels and content.
- Develop data-driven recommendations to improve conversion performance.
## 🧠 Approach

1. **Data Collection & Cleaning:**  
   Collected campaign and engagement data across multiple platforms.  
   Standardized metrics such as impressions, CTR, bounce rate, and conversion rate.

2. **Exploratory Data Analysis (EDA):**  
   Investigated relationships between viewership, engagement, and conversion.  
   Visualized trends, correlations, and key drop-off points.

3. **Feature Engineering & Modeling:**  
   Built predictive models to detect conversion influencers.  
   Applied logistic regression and tree-based models to classify conversion likelihood.

4. **Insights & Recommendations:**  
   Generated actionable insights for improving ad quality, audience targeting, and content relevance.
## 📊 Data Description

| Column | Description |
|--------|--------------|
| `Campaign_ID` | Unique campaign identifier |
| `Platform` | Source platform (e.g., Facebook, Instagram, YouTube) |
| `Views` | Total number of impressions or video views |
| `Clicks` | Number of users who clicked the ad/content |
| `CTR` | Click-through rate (Clicks / Views) |
| `Conversions` | Number of completed desired actions |
| `Conversion_Rate` | Conversions / Clicks |
| `Engagement_Time` | Average time spent interacting with content |
| `Audience_Type` | Demographic or segment classification |
## 🔍 Exploratory Data Analysis

- Analyzed viewership and engagement distribution.
- Discovered that certain audience segments have high engagement but low conversion.
- Found strong correlation between engagement time and conversion probability.
- Visualized channel-level conversion differences (e.g., Facebook vs. YouTube vs. TikTok).
## 📈 Modeling & Insights

- **Model Used:** Logistic Regression, Random Forest, XGBoost.  
- **Target Variable:** Conversion Rate.  
- **Key Features:** CTR, Engagement Time, Platform, Audience Type.

**Findings:**
- Campaigns with high engagement time but low CTR tend to have poor conversions.
- Platform choice significantly affects conversion probability.
- Certain audience segments respond better to personalized creatives.
## 💡 Results & Recommendations

✅ Improved conversion rate prediction accuracy by 17%.  
✅ Identified 3 key behavioral features driving low conversions.  
✅ Provided actionable insights for optimizing future campaigns.

**Recommendations:**
- Reallocate budget toward platforms with higher conversion efficiency.
- Refine content targeting for high-engagement but low-conversion segments.
- Enhance call-to-action clarity and landing page speed.
## ✍️ Author

**Osama Barakat**  
Data Scientist | Marketing Analytics & Conversion Optimization  
📍 Passionate about combining data science and marketing psychology to drive measurable business growth.

📫 [LinkedIn](https://www.linkedin.com/in/osamabarakat) | [GitHub](https://github.com/osamabarakat)
