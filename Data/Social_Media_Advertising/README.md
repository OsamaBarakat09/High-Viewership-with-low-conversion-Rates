# 📊 Social Media Advertising Analysis — High Viewership with Low Conversion Rates

This section of the larger **"High Viewership with Low Conversion Rates"** project focuses specifically on **social media advertising campaigns**.  

While many campaigns achieve high impressions, clicks, or engagement metrics, they often fail to convert that attention into **meaningful business outcomes** — such as purchases, sign-ups, or subscriptions.  

This analysis applies **advanced data science and marketing analytics techniques** to uncover the **key factors behind low conversion rates on social media platforms**, including:

- Audience behavior patterns that drive engagement but do not translate into conversions.  
- The effectiveness of different advertising channels, content types, and targeting strategies.  
- Actionable insights to improve campaign efficiency, ROI, and targeting precision.

By focusing on this part of the broader project, we aim to provide a **clear, data-driven understanding of social media performance**, enabling businesses and marketers to **maximize conversion while maintaining high engagement levels**.

---
## 📌 Project Overview / Purpose

This folder contains the **Social Media Advertising datasets**, which are a key part of the larger **"High Viewership with Low Conversion Rates"** project.  

The primary objective of this subset is to analyze **why social media campaigns often attract high engagement but fail to convert views and clicks into meaningful business outcomes**, such as purchases, sign-ups, or subscriptions.  

By examining campaign performance, audience demographics, and detailed engagement metrics, this data enables:

- **Identification of high-viewership campaigns with low conversion rates.**  
- **Analysis of audience behavior and segment performance** to understand which user groups engage but do not convert.  
- **Evaluation of campaign efficiency** across channels, content, and targeting strategies.  
- **Data-driven recommendations** to optimize ad spend, content, and targeting for improved ROI.  

This dataset serves as the foundation for **predictive modeling, segmentation analysis, and actionable marketing insights**, providing marketers and data analysts with the tools to **maximize conversion while maintaining high engagement**.

---
## 🗂️ Data Sources / Origin

The datasets in this folder are derived from a **Kaggle public dataset** related to social media advertising.  
They have been **adapted and processed** to simulate real-world scenarios similar to the campaigns conducted by my company. Due to confidentiality, the exact company data cannot be shared publicly.  

All datasets are provided as **CSV files** for easy use in analysis and modeling.  

Key notes about the data:

- No APIs were used to collect or generate the data.  
- The data has been prepared for analysis with **no licensing restrictions or usage limitations** applied.  
- All modifications, cleaning, and preprocessing have been performed to make the datasets **ready for exploration, merging, and modeling**.

---
## ⚙️ Dependencies

To effectively work with the datasets in this folder and perform analysis, the following tools and libraries are recommended:

- 🐍 **Python 3.8+** – The primary programming language used for data analysis and modeling.  
- 📊 **pandas** – For loading, cleaning, merging, and manipulating CSV datasets.  
- 🔢 **NumPy** – For numerical operations, calculations, and array manipulations.  
- 📉 **matplotlib** – For creating visualizations of campaign performance and audience metrics.  
- 📈 **seaborn** – For advanced statistical visualizations, including distributions and correlations.  
- 🧠 **scikit-learn** – For predictive modeling, classification, and clustering of high-value audience segments.  
- 🔍 **Jupyter Notebook / JupyterLab** – Recommended environment for exploratory data analysis, visualization, and step-by-step experimentation.  

> 💡 **Optional / Additional Tools:**  
> - 🗃️ **OpenPyXL** or **xlrd** – If exporting or reading Excel files in future analyses.  
> - 📦 **Plotly** – For interactive visualizations of engagement, CTR, and conversion rates.  
> - 🧹 **Missingno** – Optional library for visualizing missing values in datasets.  

These dependencies provide a **comprehensive toolkit** for cleaning, exploring, and analyzing the social media advertising data, while supporting **predictive modeling and actionable insights**.

---

## 🚨 Problem Statement

Social media campaigns often generate **large volumes of traffic and engagement metrics** — such as impressions, clicks, likes, shares, or video views — yet fail to convert this attention into **meaningful business outcomes** like purchases, sign-ups, or subscriptions.

This analysis focuses on understanding **why high engagement does not necessarily lead to high conversions** on social media platforms. Specifically, it aims to:

- **Identify audience behavior patterns** that result in high engagement but low conversion, revealing drop-off points in the user journey.  
- **Evaluate the effectiveness of marketing channels, campaign content, and targeting strategies** to determine which factors contribute to underperformance.  
- **Develop actionable, data-driven recommendations** that optimize campaigns for better conversion rates, improved ROI, and more efficient allocation of marketing resources.

By clearly diagnosing these gaps, this study provides a **strategic foundation for marketers** to convert engagement into tangible outcomes while maintaining high audience interaction.

---

## 🧠 Approach

1. **Data Collection & Cleaning**  
   - Collected campaign, performance, and audience demographic data across multiple platforms.  
   - Standardized metrics such as **impressions, clicks, CTR, conversion rate, ROI, and engagement scores**.

2. **Exploratory Data Analysis (EDA)**  
   - Investigated relationships between **viewership, engagement, and conversion**.  
   - Visualized trends, correlations, and key drop-off points across campaigns, channels, and audience segments.

3. **Feature Engineering & Modeling**  
   - Built predictive models to identify conversion influencers.  
   - Applied **logistic regression, tree-based models, and ensemble methods** to classify conversion likelihood and identify high-value audiences.

4. **Insights & Recommendations**  
   - Generated actionable insights to **optimize ad targeting, creative strategy, and channel allocation**.

---

## 📊 Original Dataset Overview

The original dataset contains a combination of **campaign performance metrics** and **audience demographic information**.  

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
| `Income_Category` | Estimated purchasing power of audience |
| `Location` | Geographic region of the audience |
| `Gender` | Gender of the audience |
| `Age_Start` / `Age_End` | Age range of the audience |

> ⚡ **Note:** To streamline the analysis and enable a more focused exploration of key aspects, the original dataset has been **strategically divided into three distinct datasets**.  
This separation allows for **independent examination of campaign performance, audience demographics, and detailed performance metrics**, while maintaining the ability to merge them for comprehensive analysis when needed.  

### **1️⃣ Campaign Info Dataset**
| Column | Description |
|--------|-------------|
| `Campaign_ID` | Unique campaign identifier |
| `Campaign_Goal` | Objective of the campaign (e.g., awareness, conversion) |
| `Duration` | Time period of the campaign |
| `Channel_Used` | Social media or advertising channel |
| `Acquisition_Cost` | Cost to acquire a customer via this campaign |
| `Language` | Primary language targeted |
| `Engagement_Score` | Combined measure of audience interaction |
| `Date` | Date of campaign launch |
| `Company` | Campaign owner / brand |

### **2️⃣ Audience / Demographics Dataset**
| Column | Description |
|--------|-------------|
| `Campaign_ID` | Unique campaign identifier |
| `Location` | Geographic location of the audience |
| `Interest` | User interests or engagement |
| `Income_Signal` | Estimated income signal (numeric proxy) |
| `Income_Category` | Categorized income group |
| `Gender` | Gender of the audience |
| `Age_Start` | Beginning of age range |
| `Age_End` | End of age range |

### **3️⃣ Performance Metrics Dataset**
| Column | Description |
|--------|-------------|
| `Campaign_ID` | Unique campaign identifier |
| `Clicks` | Number of clicks received |
| `Impressions` | Number of times the campaign was shown |
| `ROI` | Return on investment for the campaign |
| `Conversion_Rate` | Percentage of users who completed desired action |
| `Acquisition_Cost` | Cost to acquire a customer through this campaign |
| `CTR` | Click-through rate |
| `CPC` | Cost per click |

---

## 🔀 Analytical Paths / Approaches

After dividing the original dataset into **Campaign Info**, **Audience/Demographics**, and **Performance Metrics**, several analytical paths are available to investigate **high viewership with low conversion**.  
Each path focuses on different aspects of campaigns, audiences, or performance, allowing for **targeted insights and actionable recommendations**.

---

### **Path 1 — Campaign Efficiency Analysis**
**Objective:** Identify campaigns that generate high engagement but fail to convert users.  

**Approach:**  
- Merge **Campaign Info** with **Performance Metrics** using `Campaign_ID`.  
- Analyze metrics such as **Engagement_Score, CTR, Conversion_Rate, ROI, Duration, Channel_Used, and Company**.  
- Compare campaigns to detect **mismatches between engagement and conversions**.  

**Expected Outcome:**  
- Pinpoint campaigns that attract attention but underperform in conversions.  
- Provide recommendations for **content optimization, channel selection, and budget reallocation**.

---

### **Path 2 — Audience Segment Analysis**
**Objective:** Determine which audience segments engage but rarely convert.  

**Approach:**  
- Merge **Audience/Demographics Dataset** with **Performance Metrics**.  
- Analyze **Conversion_Rate, ROI, and Engagement_Score** across segments defined by **Income_Category, Age, Gender, Interest, and Location**.  
- Identify **audience groups that generate high impressions or clicks but low conversions**.  

**Expected Outcome:**  
- Highlight target segments for **re-marketing or refined targeting**.  
- Inform strategies to **personalize campaigns** and improve conversion efficiency.

---

### **Path 3 — Revenue & Cost Optimization**
**Objective:** Optimize marketing spend and maximize return on investment.  

**Approach:**  
- Merge all three datasets for a **holistic view** of campaigns and audiences.  
- Calculate **Cost per Acquisition (CPA), ROI, CPC, and Conversion_Rate** for campaigns and audience segments.  
- Identify **high-cost campaigns or segments that yield low returns**.  

**Expected Outcome:**  
- Prioritize campaigns and segments with **high ROI and low acquisition cost**.  
- Provide **budget optimization strategies** for future campaigns.

---

### **Path 4 — High-Value Segment Prediction**
**Objective:** Predict audience segments most likely to convert.  

**Approach:**  
- Merge all datasets and engineer features from campaign, audience, and performance data.  
- Use **machine learning models** such as Logistic Regression, Random Forest, or XGBoost to predict **conversion likelihood**.  
- Focus on **high-potential segments** for targeting in upcoming campaigns.  

**Expected Outcome:**  
- Develop predictive models to **anticipate conversion behavior**.  
- Identify and prioritize **audience segments with the highest conversion potential**.

---

### **Path 5 — Channel & Language Optimization**
**Objective:** Evaluate the effectiveness of different advertising channels and languages.  

**Approach:**  
- Analyze **Conversion_Rate, Engagement_Score, and ROI** by **Channel_Used** and **Language**.  
- Compare channels to identify where **high engagement does not translate into conversions**.  

**Expected Outcome:**  
- Recommend **channel or language-specific strategies** to improve conversion rates.  
- Optimize ad placement and creative content for **maximum impact**.

---

### **Path 6 — Time-Based Analysis**
**Objective:** Identify how campaign timing affects engagement and conversions.  

**Approach:**  
- Use **Date** and **Duration** columns to analyze performance over **daily, weekly, or seasonal intervals**.  
- Examine **temporal patterns** in engagement, CTR, and Conversion_Rate.  

**Expected Outcome:**  
- Detect **peak performance periods** and identify times when engagement does not lead to conversions.  
- Support **time-optimized campaign scheduling** for better ROI.

---

### **Advanced / Combined Approaches**
**Objective:** Apply multi-dimensional analysis for deeper insights.  

**Approach:**  
- Cluster campaigns based on **Engagement_Score and ROI** to identify **high-viewership, low-conversion groups**.  
- Analyze **Interests, Income_Category, and Demographics** to design targeted re-marketing strategies.  
- Predict **Lifetime Value (LTV)** of audience segments to prioritize long-term profitability.  

**Expected Outcome:**  
- Enable **strategic decision-making** by combining engagement, conversion, and demographic insights.  
- Provide **comprehensive recommendations** for audience targeting, budget allocation, and campaign optimization.

## 💡 Expected Outcomes

- Identification of **high-viewership but low-conversion campaigns**.  
- Recognition of **audience segments with high engagement but low conversion**.  
- Optimization of **budget, channels, and ad creatives**.  
- Predictive insights for **high-value target audiences**.  
- Data-driven recommendations to improve **ROI and conversion efficiency**.

---

## ✍️ Author

**Osama Barakat**  
Data Scientist | Marketing Analytics & Conversion Optimization  
📍 Passionate about combining data science and marketing psychology to drive measurable business growth.  

📫 **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/osama-barakat-9b1b511b8/)
