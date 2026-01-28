
# CodeX Energy Drink – Marketing & Consumer Insights (Power BI)

## 📌 Project Overview
CodeX is a German beverage company that recently launched its energy drink in 10 cities across India.  
The marketing team conducted a large-scale consumer survey to understand brand perception, consumer preferences, competitive positioning, and marketing effectiveness.

In this project, I played the role of **Peter Pandey, Marketing Data Analyst**, and converted raw survey data into **actionable, CMO-ready insights** using Power BI.

---

## 📊 Dataset Description
The analysis is based on survey responses collected from **10,000 energy drink consumers** across 10 Indian cities.

**Tables used:**
- `fact_survey_responses.csv` – Survey responses capturing preferences, ratings, marketing influence, and purchase behavior  
- `dim_respondents.csv` – Respondent demographics (age, gender, city)  
- `dim_cities.csv` – City-level information  

The data model follows a clean analytical structure:
- **City → Respondent → Survey Response**
- Single-direction relationships to ensure accurate filter propagation

---

## 🎯 Business Objectives
- Understand consumer behavior and preferences in the energy drink category  
- Analyze youth (15–30) preferences and marketing responsiveness  
- Evaluate CodeX’s competitive position against market leaders  
- Identify effective marketing channels and city-level opportunities  
- Provide data-driven recommendations for product development  

---

## 📈 Dashboard Structure (7 Pages)

### 1️⃣ Executive Overview  
High-level KPIs covering:
- Survey reach and sample distribution  
- CodeX brand awareness and average ratings  
- City-level performance snapshot  

### 2️⃣ Consumer Behavior & Preferences  
- Brand preference distribution  
- Purchase locations and consumption occasions  
- Ingredient and packaging preferences  
- Embedded youth vs non-youth comparison  

### 3️⃣ Competition Analysis & Brand Awareness  
- Market leaders vs CodeX comparison  
- Awareness vs preference analysis  
- Reasons consumers prefer competing brands  

### 4️⃣ Marketing Channels & Effectiveness  
- Overall channel influence  
- CodeX-specific channel performance  
- Youth vs non-youth marketing response  

### 5️⃣ Brand Penetration & City Focus  
- City-wise brand ratings and awareness  
- City prioritization matrix (Expand / Fix / Defend / Monitor)  

### 6️⃣ Purchase Behavior & Decision Drivers  
- Preferred purchase channels  
- Price sensitivity and limited edition impact  
- Key purchase influencing factors  

### 7️⃣ Product Development & Strategic Recommendations  
- Rating comparison across product dimensions (Taste, Branding, Availability)  
- Youth-driven innovation signals  
- Clear recommendations for business focus areas  

---

## 🔍 Key Insights
- Youth consumers respond significantly better to digital and influencer-led marketing channels  
- Taste and availability are stronger drivers of brand preference than branding alone  
- Several cities show high satisfaction but low awareness, indicating untapped growth potential  
- Limited edition packaging has higher appeal among younger consumers  

---

## 🛠 Tools & Skills Used
- **Power BI** – Data modeling, DAX measures, interactive dashboards  
- **Power Query** – Data cleaning and feature engineering  
- **Data Analysis** – Consumer insights, segmentation, and storytelling  

---

## 💼 Business Impact
This dashboard enables leadership to:
- Optimize marketing spend by channel and city  
- Prioritize youth-focused branding strategies  
- Identify product improvement areas before large-scale expansion  

---

## 📂 Repository Structure
```
├── data/
│   ├── fact_survey_responses.csv
│   ├── dim_respondents.csv
│   └── dim_cities.csv
│
├── powerbi/
│   └── CodeX_Marketing_Insights.pbix
│
├── screenshots/
│   └── dashboard_pages.png
│
└── README.md
```

---

## 📌 Author
**Karthikeyan**  
Aspiring Data Analyst | Power BI | SQL | Data Storytelling  
