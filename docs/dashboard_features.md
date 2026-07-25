# 📈 Dashboard Features — Detailed Documentation

This document provides an in-depth breakdown of every visualization in the Airbnb Data Analytics Dashboard, including design rationale, data sources, and analytical purpose.

---

## Dashboard Layout

The dashboard is organized into a **2-row layout** for maximum readability:

| Row | Visualizations | Focus |
|-----|---------------|-------|
| **Top** | Avg Price Per Bedroom + Distinct Count of Bedroom Listings | Property-level pricing and market composition |
| **Bottom** | Price Per Zipcode (Map) + Price by Zipcode (Bar) + Revenue for Year | Geographic pricing and temporal revenue trends |

---

## Visualization 1: Average Price Per Bedroom

### Description
A vertical bar chart displaying the average nightly price for Airbnb listings, segmented by the number of bedrooms (1 through 6).

### Design Choices
- **Chart Type:** Vertical bar chart — ideal for comparing discrete categories
- **Color:** Consistent dark blue — avoids unnecessary color complexity for a single-dimension comparison
- **Labels:** Value labels displayed on each bar for immediate readability
- **Axis:** Y-axis shows price in USD; X-axis shows bedroom count

### Data Points

| Bedrooms | Average Price (USD) |
|----------|-------------------|
| 1 | $96.2 |
| 2 | $175.4 |
| 3 | $249.7 |
| 4 | $315.4 |
| 5 | $450.0 |
| 6 | $584.8 |

### Analytical Value
- Demonstrates a clear positive correlation between bedroom count and pricing
- The non-linear price increase (especially 4→5 and 5→6 bedrooms) suggests premium pricing for large-group accommodations
- Helps hosts benchmark their pricing against market averages

---

## Visualization 2: Price Per Zipcode (Geographic Map)

### Description
A filled choropleth map of the Seattle metropolitan area, with each ZIP code region color-coded by average listing price. Price values are annotated directly on the map.

### Design Choices
- **Chart Type:** Filled map (choropleth) — provides immediate spatial context
- **Color Encoding:** Color intensity correlates with price level
- **Base Map:** OpenStreetMap tiles for geographic reference
- **Annotations:** ZIP code numbers and average prices overlaid on each region

### Key Observations
- Downtown and waterfront ZIP codes show higher price concentrations
- Outer suburban areas display consistently lower pricing
- The map enables quick visual identification of "hot zones" and "cold zones"

### Analytical Value
- Essential for location-based investment decisions
- Helps travelers identify budget-friendly vs. premium areas
- Provides spatial context that bar charts alone cannot convey

---

## Visualization 3: Price by Zipcode (Bar Chart)

### Description
A vertical bar chart ranking all Seattle ZIP codes by average listing price in descending order. Each bar is color-coded by ZIP code for visual distinction.

### Design Choices
- **Chart Type:** Vertical bar chart — enables precise comparison and ranking
- **Color:** Distinct color per ZIP code matching the map legend for cross-reference
- **Sorting:** Descending order by average price — highlights top-performing areas immediately
- **Legend:** Full ZIP code color legend positioned for easy reference

### Top ZIP Codes by Average Price
1. **98119** — Highest average prices (~$200+)
2. **98101** — Downtown core, premium pricing
3. **98109** — South Lake Union / Queen Anne area

### Analytical Value
- Provides an exact ranking that the map cannot offer
- Enables quick competitive benchmarking across neighborhoods
- When used alongside the map, creates a comprehensive geographic pricing story

---

## Visualization 4: Revenue for Year (Time Series)

### Description
A continuous line chart showing total weekly revenue across all Airbnb listings throughout the year 2016. The x-axis spans from January to December, with the y-axis showing revenue in USD.

### Design Choices
- **Chart Type:** Line chart — ideal for showing trends over continuous time
- **Granularity:** Weekly aggregation — balances detail with readability
- **Color:** Single dark blue line — clean, professional appearance
- **Y-Axis:** Revenue formatted in K notation (e.g., 500K, 1,000K, 2,000K)

### Key Temporal Patterns

| Period | Revenue Range | Trend |
|--------|--------------|-------|
| Jan – Feb | $500K – $900K | Low baseline (winter) |
| Mar – May | $900K – $1,500K | Steep upward growth |
| Jun – Aug | $1,500K – $2,100K | Peak season plateau |
| Sep – Nov | $1,800K – $2,000K | Sustained high levels |
| Dec | ~$2,000K+ | Year-end strength |

### Analytical Value
- Identifies optimal periods for dynamic pricing adjustments
- Helps hosts plan availability and maintenance windows
- Reveals the overall market growth trajectory

---

## Visualization 5: Distinct Count of Bedroom Listings

### Description
A summary reference table displaying the total number of distinct listings for each bedroom category.

### Design Choices
- **Format:** Clean text table — prioritizes exact numbers over visual approximation
- **Positioning:** Right panel — serves as a contextual reference for the pricing chart
- **Filtering Note:** Displays that the view is filtered on bedrooms, keeping 6 of 8 members

### Listing Distribution

| Bedrooms | Listing Count | Market Share |
|----------|--------------|-------------|
| 1 | 1,811 | ~70.2% |
| 2 | 483 | ~18.7% |
| 3 | 206 | ~8.0% |
| 4 | 55 | ~2.1% |
| 5 | 20 | ~0.8% |
| 6 | 5 | ~0.2% |

### Analytical Value
- Contextualizes the pricing data — high prices for 5-6 bedroom listings are explained by extreme scarcity
- Identifies the dominant market segment (1-bedroom = 70%+ of listings)
- Highlights investment opportunities in under-supplied bedroom categories

---

## Cross-Visualization Insights

The true power of this dashboard emerges when visualizations are analyzed **together**:

1. **Price + Supply Relationship:** The bar chart and listing count table together reveal an inverse relationship — fewer listings correlate with higher prices.
2. **Geographic + Pricing:** The map and ZIP code bar chart together provide both spatial and precise numerical views of the same data.
3. **Time + Price:** Revenue trends combined with bedroom pricing help explain which property types drive seasonal revenue spikes.

---

<p align="center"><em>Each visualization was designed to answer a specific question while contributing to the overall analytical narrative.</em></p>
