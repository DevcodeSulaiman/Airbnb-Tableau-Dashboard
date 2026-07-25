# 📋 Project Overview — Airbnb Data Analytics Dashboard

## Introduction

This document provides an in-depth overview of the **Airbnb Data Analytics Dashboard** project, which analyzes the Seattle, WA Airbnb market using data from three primary sources: listings, reviews, and calendar availability.

The project demonstrates a complete analytics workflow — from raw data ingestion and cleaning to interactive dashboard creation and business insight extraction.

---

## Background

The short-term rental industry, led by platforms like Airbnb, has transformed the hospitality landscape worldwide. As the market matures, data-driven decision-making becomes critical for:

- **Hosts** optimizing pricing and availability strategies
- **Investors** identifying high-yield neighborhoods and property types
- **Urban planners** understanding rental market impacts on housing
- **Travelers** finding the best value in accommodations

This project addresses these needs by building a centralized analytics dashboard that transforms raw Airbnb data into visual, actionable insights.

---

## Scope

| Dimension | Detail |
|-----------|--------|
| **Market** | Seattle, WA, USA |
| **Time Period** | Full year 2016 (calendar data) |
| **Data Sources** | Airbnb Open Data (Inside Airbnb initiative) |
| **Analysis Focus** | Pricing, geographic trends, revenue patterns, and market composition |
| **Tools** | Microsoft Excel (data prep), Tableau Public (visualization) |

---

## Methodology

### 1. Data Acquisition
Raw CSV files were obtained from the Airbnb Open Data initiative, containing listings metadata, guest reviews, and daily calendar availability records.

### 2. Data Cleaning & Transformation
All data cleaning was performed in Microsoft Excel:
- Removed duplicates and null records
- Standardized column naming conventions
- Converted price strings to numeric values
- Parsed and formatted date fields
- Validated geographic data (ZIP codes, coordinates)
- Cross-referenced datasets for consistency

### 3. Data Integration
The cleaned datasets were consolidated into a single Excel workbook (`Tableau Full Project.xlsx`) with multiple sheets, structured for optimal Tableau ingestion.

### 4. Dashboard Design
Five complementary visualizations were designed in Tableau to address distinct analytical questions:
- Bar charts for pricing comparison
- Choropleth map for geographic analysis
- Line chart for temporal revenue trends
- Summary table for market composition

### 5. Insight Extraction
Key business insights were derived from the dashboard, categorized into pricing, geographic, revenue, and market composition themes.

---

## Target Audience

This project is designed for:

- 📊 **Data Analysts** — As a reference for Tableau dashboard projects
- 💼 **Recruiters & Hiring Managers** — As a portfolio demonstration of analytical skills
- 🏠 **Real Estate Professionals** — As a market analysis tool for the Seattle rental market
- 🎓 **Students** — As a learning resource for the data analytics workflow

---

## Key Deliverables

1. **Interactive Tableau Dashboard** — Multi-view dashboard with 5 visualizations
2. **Cleaned Dataset** — Processed and validated data ready for analysis
3. **Documentation** — Comprehensive project documentation (this file and related docs)
4. **Business Insights** — 12 actionable insights derived from the analysis

---

## Contact

For questions, feedback, or collaboration opportunities, please open an [Issue](../../issues) or submit a [Pull Request](../../pulls).

---

<p align="center"><em>📊 Data tells a story — this project helps you read it.</em></p>
