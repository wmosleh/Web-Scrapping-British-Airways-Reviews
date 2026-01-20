# 🌐 Web Scraping & NLP Analytics for Airline Customer Intelligence  
**Notebook:** `Web scraping to gain company insights.ipynb`  
**Author:** **[Wissam Mosleh](https://github.com/wmosleh)**  
🔗 [GitHub Portfolio](https://github.com/wmosleh)

---

## Overview
This project implements an **end-to-end web scraping and NLP analytics pipeline** to extract, structure, and analyze **airline customer reviews** for business intelligence and decision-support systems.

The system is demonstrated using **1,000 British Airways customer reviews scraped from Skytrax**, transforming unstructured text into **quantitative insights on customer experience, service quality, and operational performance**.

The architecture and methods are directly transferable to:
- ✈️ Airline customer experience monitoring
- 📊 Service quality and brand perception analytics
- 🧠 Operations and delay impact analysis
- 📑 Compliance and reputation tracking systems

---

## Business Problem
Airlines receive large volumes of unstructured customer feedback across multiple platforms. Manual review is:
- Time-consuming
- Subjective
- Difficult to scale

Organizations need **automated, auditable analytics pipelines** that convert raw text into **measurable KPIs and strategic insights**.

---

## Solution
Built a **modular web scraping and NLP pipeline** that:
- Extracts public airline reviews from Skytrax
- Cleans and normalizes raw text
- Converts text into structured numerical features
- Applies dimensionality reduction and topic modeling
- Classifies sentiment at scale
- Produces interactive visualizations for stakeholder analysis

---

## Pipeline Workflow
**Target URLs → Web Scraping → Text Cleaning & Normalization → Feature Engineering (BoW / PCA) → Sentiment Classification → Topic Modeling (LDA) → Visualization & Reporting**

---

## Key Features
- ✅ Automated scraping of **1,000 airline reviews**
- ✅ Bag of Words frequency analysis (Top 10 keywords)
- ✅ **Principal Component Analysis (PCA)** with 2 and 3 components
- ✅ **Sentiment Analysis** (Positive / Neutral / Negative)
- ✅ **LDA Topic Modeling** (3 dominant customer experience topics)
- ✅ **Word Cloud Visualization**
- ✅ Interactive topic visualization (`lda_vis.html`)
- ✅ Analytics-ready DataFrames for BI and reporting

---

## Results & Insights

### Sentiment Distribution
- **57% Positive**
- **42.7% Negative**
- **0.3% Neutral**

### Recommendation Rate
- **67.8% did NOT recommend** the airline
- **32.2% recommended** the airline

### Top Frequent Words
`flight`, `ba`, `seat`, `service`, `time`, `hour`, `food`, `crew`, `fly`, `good`  
➡ Indicates strong focus on **experience, staff, and onboard service**

---

## Dimensionality Reduction (PCA)

### Top Features — PC1
`flight`, `ba`, `get`, `hour`, `tell`, `would`, `book`, `call`, `day`, `could`  
➡ Reflects **booking, time, and customer communication themes**

### Top Features — PC2
`seat`, `class`, `business`, `good`, `cabin`, `food`, `crew`, `passenger`  
➡ Represents **service quality and product experience**

### Top Features — PC3
`customer`, `airline`, `british`, `call`, `crew`, `flight`  
➡ Highlights **brand perception and customer service interactions**

---

## Topic Modeling (LDA Results)

### Topic 1 — Operations & Boarding
`flight`, `staff`, `time`, `crew`, `delay`, `check`, `gate`, `boarding`

### Topic 2 — Customer Service & Disruptions
`customer`, `airline`, `call`, `cancel`, `tell`, `hour`

### Topic 3 — Cabin & Product Experience
`seat`, `class`, `food`, `business`, `service`, `cabin`, `crew`

📊 Interactive Visualization:  
`lda_vis.html`

---

## Aviation & Enterprise Transferability
This pipeline directly supports:
- ✈️ Airline customer experience analytics
- 📊 Service quality KPI monitoring
- 🛠️ Disruption and delay impact analysis
- 🧠 Brand and reputation intelligence
- 📑 Executive dashboards and BI systems

---

## Tech Stack
| Category | Tools |
|----------|-------|
| Language | Python |
| Scraping | Requests, BeautifulSoup |
| NLP | NLTK, Scikit-learn |
| Data | Pandas, NumPy |
| Visualization | WordCloud, PyLDAvis |
| Analysis | Jupyter Notebook |

---

## How to Run

### Install Dependencies
```bash
pip install requests beautifulsoup4 pandas numpy nltk scikit-learn wordcloud pyldavis jupyter
