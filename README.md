# 🌐 Web Scraping for Company Intelligence & Market Insights  
**Notebook:** `Web scraping to gain company insights.ipynb`  
**Author:** **[Wissam Mosleh](https://github.com/wmosleh)**  
🔗 [GitHub Portfolio](https://github.com/wmosleh)

---

## Overview
This notebook demonstrates an **end-to-end web scraping and data analytics pipeline** for extracting, structuring, and analyzing publicly available company information to support **business intelligence, market research, and decision-support workflows**.

The system automates the collection of unstructured web data and transforms it into **clean, analytics-ready datasets** that can be used for:
- Competitive analysis
- Company profiling
- Market trend discovery
- Strategic reporting and dashboards

The techniques and architecture are directly transferable to **aviation, enterprise analytics, and digital transformation use cases**, such as monitoring airline competitors, tracking industry news, and building intelligence feeds for operations and strategy teams.

---

## Problem
Public company and market information is often:
- Distributed across multiple websites
- Unstructured and inconsistent
- Time-consuming to collect manually

This makes it difficult to build **scalable, repeatable, and auditable intelligence pipelines** for analytics and reporting.

---

## Solution
This notebook implements a **modular web scraping and analytics workflow** that:
- Crawls and retrieves structured and semi-structured web content
- Parses HTML into normalized tabular formats
- Cleans and validates extracted fields
- Stores data in analytics-ready DataFrames
- Supports downstream visualization, reporting, and modeling

---

## Pipeline Workflow
**Target URLs → HTTP Requests → HTML Parsing → Data Cleaning → Structuring & Validation → Analytics & Reporting**

---

## Key Features
- ✅ Automated web data extraction using HTTP requests
- ✅ HTML parsing and field normalization (company name, description, sector, key metrics, etc.)
- ✅ Data cleaning and validation pipeline
- ✅ Pandas-based analytics-ready DataFrames
- ✅ Modular, reusable scraping functions
- ✅ Export support (CSV / Excel) for BI and dashboards
- ✅ Error handling and logging for robust execution

---

## Tech Stack
| Category | Tools |
|----------|-------|
| Language | Python |
| Scraping | Requests, BeautifulSoup |
| Data | Pandas, NumPy |
| Analysis | Jupyter Notebook |
| Export | CSV / Excel |

---

## How to Run

### 1. Install Dependencies
```bash
pip install requests beautifulsoup4 pandas numpy jupyter
