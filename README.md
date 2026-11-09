# 📊 AI Job Market Dashboard (Power BI)

An interactive 3-page Power BI dashboard that explores the AI job market through three questions: **Where is the demand? What does it pay? Which skills matter?**

---

## 🎯 Objectives
- Identify which industries, countries and work types have the highest demand for AI roles
- Analyse how compensation varies by experience level, industry and country
- Compare salary, bonus and benefits to understand the full pay structure
- Find the most requested skills and the certifications linked to higher pay
- Assess job roles by growth potential and automation risk to understand career outlook

---

## Dataset:
from Kaggle global_ai_jobs_2026

## 📑 Dashboard Pages

### 1. Market Overview
- KPIs: total job postings, total openings, average salary and fully remote share
- Job postings by work type (remote / hybrid / on-site)
- Job postings by industry (treemap)
- Demand vs competition by industry (scatter plot)
- Geographic distribution of jobs (map) with a custom tooltip page
- Filters: experience level, industry, continent

### 2. Compensation Overview
- KPIs: equity salary gap, average total compensation, average bonus value, executive vs entry-level pay multiple
- Average salary by experience level
- Share of pay: salary vs bonus vs benefits
- Average salary by country (filled map)
- Decomposition tree to break down salary by experience level, AI specialization, industry and job title
- Filters: experience level, industry, continent

### 3. Skills and Outlooks
- Top 10 most requested skills
- Average salary by certification
- Growth vs automation-risk quadrant of job roles, sized by number of openings
- Filters: certifications, industry, job type, job title

---

## 🖼️ Screenshots

### Market Overview
![Market Overview](Market-Overview.png)

### Compensation Overview
![Compensation Overview](Compensation-Overview.png)

### Skills and Outlooks
![Skills and Outlooks](skills-outlooks.png)

---

## 🛠️ Tools & Features Used
- Power BI Desktop
- DAX measures (KPIs, pay premiums, ratios, quadrant classification)
- Slicers and cross-filtering
- Bookmarks (reset filters) and page navigation buttons
- Custom tooltip page
- Decomposition tree, scatter, treemap, donut and filled map visuals
- Custom theme

---

## ▶️ How to Open
1. Download `H006_Smruti_Gangan_Powerbi_Dashboard.pbix` from this repository
2. Open it in **Power BI Desktop** (free for Windows)
3. Use the arrow buttons to move between pages and the reset button to clear filters

---

## 👩‍💻 Author
**Smruti Gangan**
