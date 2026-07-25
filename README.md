<p align="center">
  <img src="assets/banner.png" alt="Airbnb Data Analytics Dashboard Banner" width="100%">
</p>

<h1 align="center">🏠 Airbnb Data Analytics Dashboard | Tableau</h1>

<p align="center">
  <em>A comprehensive data analytics project exploring Airbnb listing trends, pricing patterns, and revenue insights using Tableau & Excel.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau"/>
  <img src="https://img.shields.io/badge/Data%20Analytics-4285F4?style=for-the-badge&logo=google-analytics&logoColor=white" alt="Data Analytics"/>
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Data%20Cleaning-FF6F00?style=for-the-badge&logo=databricks&logoColor=white" alt="Data Cleaning"/>
  <img src="https://img.shields.io/badge/Dashboard-0052CC?style=for-the-badge&logo=dashlane&logoColor=white" alt="Dashboard"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-orange?style=flat-square" alt="PRs Welcome"/>
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square" alt="Made with Love"/>
</p>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Objectives](#-objectives)
- [Tools & Technologies](#%EF%B8%8F-tools--technologies)
- [Project Workflow](#-project-workflow)
- [Dataset Description](#-dataset-description)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Dashboard Features](#-dashboard-features)
- [Key Insights](#-key-insights)
- [Skills Demonstrated](#-skills-demonstrated)
- [Dashboard Preview](#-dashboard-preview)
- [Installation & Usage](#-installation--usage)
- [Repository Structure](#-repository-structure)
- [Future Improvements](#-future-improvements)
- [Learning Outcomes](#-learning-outcomes)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔍 Project Overview

This project presents an **end-to-end data analytics solution** built on the Airbnb Listings dataset for the Seattle, WA market. The goal was to transform raw, unstructured CSV data into a polished, interactive Tableau dashboard that delivers **actionable business insights** for stakeholders—including property managers, investors, and tourism analysts.

The pipeline encompasses the full analytics lifecycle: data acquisition, cleaning and transformation in Microsoft Excel, and interactive visualization in Tableau Public. Every design choice—from color encoding to chart selection—was made with **clarity, accessibility, and storytelling** in mind.

> 💡 **Why this project matters:** The short-term rental market is a multi-billion-dollar industry. Understanding pricing dynamics, geographic patterns, and seasonal revenue trends is critical for data-driven decision-making in hospitality and real estate.

---

## 💼 Business Problem

Airbnb hosts, property investors, and market analysts often struggle to answer fundamental questions such as:

- **What is the optimal pricing strategy** based on property size?
- **Which neighborhoods or ZIP codes** command premium rental rates?
- **When are the peak revenue periods** throughout the year?
- **How does bedroom count** impact listing competitiveness and pricing?
- **Where should new investment** be concentrated for maximum ROI?

Without a centralized analytical tool, these questions remain buried in spreadsheets. This project bridges that gap by providing a **single-pane-of-glass dashboard** that distills thousands of records into clear, visual answers.

---

## 🎯 Objectives

| # | Objective | Status |
|---|-----------|--------|
| 1 | Clean and prepare raw Airbnb CSV data for analysis | ✅ Complete |
| 2 | Perform exploratory data analysis to identify trends | ✅ Complete |
| 3 | Build an interactive Tableau dashboard with multiple views | ✅ Complete |
| 4 | Derive actionable business insights from the data | ✅ Complete |
| 5 | Document findings and methodology professionally | ✅ Complete |

---

## 🛠️ Tools & Technologies

<table>
  <tr>
    <td align="center" width="150">
      <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau"/><br/>
      <strong>Tableau Public</strong><br/>
      <sub>Dashboard & Visualization</sub>
    </td>
    <td align="center" width="150">
      <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel"/><br/>
      <strong>Microsoft Excel</strong><br/>
      <sub>Data Cleaning & Prep</sub>
    </td>
    <td align="center" width="150">
      <img src="https://img.shields.io/badge/Data%20Cleaning-FF6F00?style=for-the-badge&logo=databricks&logoColor=white" alt="Cleaning"/><br/>
      <strong>Data Cleaning</strong><br/>
      <sub>Quality Assurance</sub>
    </td>
    <td align="center" width="150">
      <img src="https://img.shields.io/badge/Visualization-0052CC?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Viz"/><br/>
      <strong>Data Visualization</strong><br/>
      <sub>Visual Storytelling</sub>
    </td>
  </tr>
</table>

---

## 🔄 Project Workflow

The project follows a structured, repeatable analytics pipeline:

```
┌─────────────────────┐
│   📥 Raw CSV Files  │     listings.csv  ·  reviews.csv  ·  calendar.csv
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│  🧹 Excel Cleaning  │     Remove duplicates, nulls, and inconsistencies
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│ 🔄 Data Transform   │     Standardize columns, correct types, format dates
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│ 📊 Import → Tableau │     Load cleaned workbook as the primary data source
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│ 🎨 Dashboard Design │     Build charts, maps, and interactive elements
└─────────┬───────────┘
          │
          ▼
┌─────────────────────┐
│ 💡 Business Insights│     Extract key findings and recommendations
└─────────────────────┘
```

---

## 📊 Dataset Description

The project utilizes the **Seattle Airbnb Open Data**, comprising three interconnected datasets:

<details>
<summary><strong>📄 Listings Dataset</strong> — <code>listings.csv</code></summary>

<br/>

| Column | Description |
|--------|-------------|
| `id` | Unique listing identifier |
| `name` | Listing title / property name |
| `host_id` | Unique host identifier |
| `host_name` | Name of the property host |
| `neighbourhood_group` | Broader geographic grouping |
| `neighbourhood` | Specific neighborhood name |
| `latitude` / `longitude` | Geographic coordinates |
| `room_type` | Type of listing (Entire home, Private room, etc.) |
| `price` | Nightly rental price (USD) |
| `minimum_nights` | Minimum booking nights required |
| `number_of_reviews` | Total review count |
| `availability_365` | Days available per year |
| `bedrooms` | Number of bedrooms |
| `zipcode` | ZIP code of the property |

> **Purpose:** Core listing attributes used for pricing analysis, geographic mapping, and bedroom-based segmentation.

</details>

<details>
<summary><strong>📝 Reviews Dataset</strong> — <code>reviews.csv</code></summary>

<br/>

| Column | Description |
|--------|-------------|
| `listing_id` | Foreign key to the listings table |
| `id` | Unique review identifier |
| `date` | Date the review was posted |
| `reviewer_id` | Unique reviewer identifier |
| `reviewer_name` | Name of the reviewer |
| `comments` | Full text of the review |

> **Purpose:** Provides temporal review data to track engagement trends and guest activity over time.

</details>

<details>
<summary><strong>📅 Calendar Dataset</strong> — <code>calendar.csv</code></summary>

<br/>

| Column | Description |
|--------|-------------|
| `listing_id` | Foreign key to the listings table |
| `date` | Calendar date |
| `available` | Availability status (`t` / `f`) |
| `price` | Listed price for the date |

> **Purpose:** Enables time-series revenue analysis and seasonal demand pattern identification across the full year.

</details>

---

## 🧹 Data Cleaning & Preparation

Data quality is the foundation of reliable analytics. The following cleaning steps were performed in **Microsoft Excel** before importing into Tableau:

| Step | Action | Impact |
|------|--------|--------|
| 1️⃣ | **Removed duplicate records** | Eliminated redundant rows to prevent inflated metrics |
| 2️⃣ | **Handled missing values** | Removed or imputed null entries in critical columns (price, bedrooms, zipcode) |
| 3️⃣ | **Standardized column names** | Ensured consistent naming conventions across all datasets |
| 4️⃣ | **Corrected data types** | Converted price fields from text (with `$` and `,`) to numeric format |
| 5️⃣ | **Formatted date columns** | Parsed and standardized date fields for proper time-series analysis |
| 6️⃣ | **Filtered irrelevant data** | Removed listings with zero price, zero availability, or incomplete geographic data |
| 7️⃣ | **Validated ZIP codes** | Ensured all ZIP codes correspond to valid Seattle metro regions |
| 8️⃣ | **Prepared joined workbook** | Combined and cross-referenced datasets into a single Tableau-ready Excel file |

> 📌 The cleaned and consolidated data is available in [`data/cleaned_data.xlsx`](data/cleaned_data.xlsx).

---

## 📈 Dashboard Features

The dashboard is composed of **five interconnected visualizations**, each designed to answer specific business questions:

---

### 1️⃣ Average Price Per Bedroom

| Detail | Description |
|--------|-------------|
| **Chart Type** | Bar Chart (Vertical) |
| **Purpose** | Shows how average nightly Airbnb prices vary by the number of bedrooms in a listing |
| **Metric** | Average Price (USD) vs. Bedroom Count (1–6) |
| **Business Insight** | Properties with more bedrooms command significantly higher prices. A 1-bedroom averages **$96.2**, while a 6-bedroom listing reaches **$584.8** — a **6× premium**. This helps hosts benchmark pricing and investors evaluate the revenue potential of larger properties. |

---

### 2️⃣ Price Per Zipcode (Geographic Map)

| Detail | Description |
|--------|-------------|
| **Chart Type** | Filled Map / Choropleth |
| **Purpose** | Provides a geographic visualization of average Airbnb pricing across Seattle ZIP codes |
| **Metric** | Average Price per ZIP code, color-encoded on the map |
| **Business Insight** | Instantly identifies **premium neighborhoods** (e.g., waterfront areas near downtown) versus **budget-friendly zones** in the outer suburbs. Essential for location-based investment decisions and competitive pricing strategies. |

---

### 3️⃣ Price by Zipcode (Bar Chart)

| Detail | Description |
|--------|-------------|
| **Chart Type** | Horizontal Bar Chart |
| **Purpose** | Ranks and compares average listing prices across all Seattle ZIP codes |
| **Metric** | Average Price (USD) per ZIP code, sorted in descending order |
| **Business Insight** | ZIP code **98119** leads with the highest average prices (~$200+), while areas like **98125** and **98133** represent the most affordable markets. This ranking enables **quick competitive benchmarking** across neighborhoods. |

---

### 4️⃣ Revenue for Year (Time Series)

| Detail | Description |
|--------|-------------|
| **Chart Type** | Line Chart (Continuous) |
| **Purpose** | Displays total revenue trends across all weeks of 2016 |
| **Metric** | Weekly Revenue (USD) over time |
| **Business Insight** | Revenue shows a **strong upward trend from Q1 through mid-year**, plateauing in summer before stabilizing in Q4. This pattern suggests **high seasonal demand** from May–August, critical for dynamic pricing strategies and capacity planning. |

---

### 5️⃣ Distinct Count of Bedroom Listings

| Detail | Description |
|--------|-------------|
| **Chart Type** | Summary Table |
| **Purpose** | Shows the distribution of listings by bedroom count |
| **Metric** | Distinct count of listing IDs per bedroom category |
| **Business Insight** | **1-bedroom listings dominate** the market with 1,811 properties (70%+ of total), while 5- and 6-bedroom listings are rare (20 and 5, respectively). This scarcity of larger properties combined with their premium pricing represents a potential **high-yield investment opportunity**. |

---

## 💡 Key Insights

Based on the comprehensive dashboard analysis, the following business insights were derived:

> ### 📊 Pricing Insights
> 1. **Six-bedroom listings command the highest average prices** at **$584.8/night** — over 6× the average one-bedroom price of $96.2.
> 2. **Price scales non-linearly with bedroom count** — the jump from 4 bedrooms ($315.4) to 5 bedrooms ($450.0) is disproportionately large, suggesting a premium for large-group accommodations.
> 3. **ZIP code 98119 is the most expensive market** with average prices exceeding $200/night, while ZIP codes like 98125 and 98133 offer budget alternatives below $80/night.

> ### 🗺️ Geographic Insights
> 4. **Waterfront and downtown-adjacent ZIP codes** consistently command premium pricing, correlating with tourist-heavy and business-travel areas.
> 5. **Southern Seattle ZIP codes** represent the most affordable rental markets, offering opportunities for budget-conscious travelers and value-oriented investment.
> 6. **Price disparity across ZIP codes exceeds 150%**, highlighting the importance of location as the single largest pricing factor.

> ### 📈 Revenue & Demand Insights
> 7. **Revenue follows a clear seasonal pattern** — climbing from under **$1M/week in January** to peaks exceeding **$2M/week by mid-year**.
> 8. **The strongest revenue growth occurs between March and June**, coinciding with the spring/early-summer travel season in the Pacific Northwest.
> 9. **Q4 revenue remains elevated** compared to Q1, suggesting sustained demand through the holiday season.

> ### 🏠 Market Composition Insights
> 10. **One-bedroom listings account for 70%+ of the total market** (1,811 out of ~2,580 listings), making it the most saturated segment.
> 11. **Properties with 5+ bedrooms represent less than 1%** of total listings, yet command the highest per-night rates — a classic low-supply, high-demand scenario.
> 12. **The inverse relationship between listing count and average price** (more bedrooms = fewer listings = higher prices) suggests that diversifying into larger properties may yield outsized returns.

---

## 🧠 Skills Demonstrated

<table>
  <tr>
    <td>✅ Data Cleaning & Preprocessing</td>
    <td>✅ Data Visualization & Design</td>
  </tr>
  <tr>
    <td>✅ Interactive Dashboard Development</td>
    <td>✅ Business Intelligence Reporting</td>
  </tr>
  <tr>
    <td>✅ Exploratory Data Analysis (EDA)</td>
    <td>✅ Tableau (Desktop / Public)</td>
  </tr>
  <tr>
    <td>✅ Microsoft Excel (Advanced)</td>
    <td>✅ Analytical & Critical Thinking</td>
  </tr>
  <tr>
    <td>✅ Data Transformation & ETL</td>
    <td>✅ Data Storytelling</td>
  </tr>
  <tr>
    <td>✅ Geographic / Spatial Analysis</td>
    <td>✅ Time-Series Analysis</td>
  </tr>
</table>

---

## 🖼️ Dashboard Preview

<p align="center">
  <img src="assets/dashboard.png?v=2" alt="Airbnb Data Analytics Dashboard" width="95%">
</p>

<p align="center"><em>📊 Interactive Tableau Dashboard — Airbnb Seattle Market Analysis (2016)</em></p>

---

## 🚀 Installation & Usage

Follow these steps to explore the project locally:

### Prerequisites

- [Tableau Public](https://public.tableau.com/en-us/s/download) (Free) or Tableau Desktop
- Microsoft Excel or any spreadsheet application

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/DevcodeSulaiman/Airbnb-Tableau-Dashboard.git

# 2. Navigate to the project directory
cd Airbnb-Tableau-Dashboard
```

3. **Open the Tableau Workbook** — Double-click `AirBnb Dashboard.twbx` to launch the dashboard in Tableau.
4. **Explore the Dashboard** — Interact with filters, hover over data points, and explore different views.
5. **Review the Data** — Open `data/cleaned_data.xlsx` or the raw CSV files in the `data/` folder for deeper analysis.
6. **Modify & Extend** — Connect additional data sources or create new worksheets in Tableau to expand the analysis.

---

## 📁 Repository Structure

```
Airbnb-Tableau-Dashboard/
│
├── 📊 AirBnb Dashboard.twbx        # Tableau Packaged Workbook
├── 🖼️ Dashboard.png                 # Dashboard screenshot (root)
├── 📄 README.md                     # Project documentation (this file)
├── 📜 LICENSE                       # MIT License
├── 🚫 .gitignore                    # Git ignore rules
│
├── 🎨 assets/                       # Visual assets
│   ├── dashboard.png                # Dashboard screenshot
│   ├── banner.png                   # Repository banner image
│   └── icons/                       # Icon assets
│
├── 📂 data/                         # Project datasets
│   ├── listings.csv                 # Raw Airbnb listings data
│   ├── reviews.csv                  # Raw reviews data
│   ├── calendar.csv                 # Raw calendar / availability data
│   └── cleaned_data.xlsx            # Cleaned & transformed data for Tableau
│
└── 📖 docs/                         # Extended documentation
    ├── project_overview.md          # Detailed project overview
    ├── dashboard_features.md        # Dashboard component documentation
    └── insights.md                  # Full business insights report
```

---

## 🔮 Future Improvements

<details>
<summary><strong>Click to expand planned enhancements</strong></summary>

<br/>

| Priority | Enhancement | Description |
|----------|-------------|-------------|
| 🔴 High | **Interactive Filters** | Add dynamic filters for room type, price range, and date selection |
| 🔴 High | **KPI Summary Cards** | Add headline metrics (total listings, avg price, total revenue, avg rating) |
| 🟡 Medium | **Revenue Forecasting** | Implement time-series forecasting using Tableau's built-in analytics |
| 🟡 Medium | **Profit Analysis** | Layer in operating costs to calculate net profit margins by area |
| 🟡 Medium | **Customer Segmentation** | Cluster guests by booking patterns and preferences |
| 🟢 Low | **Review Sentiment Analysis** | Apply NLP to guest reviews for qualitative insights |
| 🟢 Low | **SQL Integration** | Migrate data pipeline to a relational database for scalability |
| 🟢 Low | **Python Automation** | Automate data cleaning and refreshes with Python (Pandas + Tableau API) |

</details>

---

## 🎓 Learning Outcomes

Through this project, the following competencies were developed and demonstrated:

- 📊 **Practical Tableau Experience** — Hands-on proficiency with Tableau Public for building multi-view dashboards from real-world data.
- 🎨 **Dashboard Design Principles** — Applied best practices in layout, color theory, chart selection, and visual hierarchy.
- 📖 **Data Storytelling** — Translated raw data into a coherent narrative that communicates insights to both technical and non-technical audiences.
- 🧹 **Data Preparation & ETL** — Developed skills in cleaning, transforming, and preparing messy data for analysis using Excel.
- 📐 **Visualization Best Practices** — Implemented appropriate chart types for different data relationships (comparison, composition, distribution, relationship).
- 💼 **Business Intelligence** — Connected analytical outputs to real business decisions around pricing, investment, and market strategy.

---

## 🤝 Contributing

Contributions are welcome and appreciated! If you'd like to improve this project:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

> 💬 Feel free to open an [Issue](../../issues) for bug reports, feature requests, or general feedback.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <strong>⭐ If you found this project useful, please consider giving it a star!</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Made with Tableau"/>
  <img src="https://img.shields.io/badge/Powered%20by-Data-4285F4?style=for-the-badge&logo=google-analytics&logoColor=white" alt="Powered by Data"/>
</p>

<p align="center">
  <sub>Built with ❤️ for the Data Analytics community</sub>
</p>
