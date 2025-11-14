# 🚴 Adventure Works Analytics Dashboard

A comprehensive multi-page Power BI dashboard providing complete business intelligence for Adventure Works, a global bikes and outdoor equipment manufacturer.

---

## 📊 Project Overview

This Power BI project delivers an enterprise-level business intelligence solution for Adventure Works, demonstrating advanced analytics capabilities across 6 interconnected dashboards. The project showcases end-to-end data modeling, complex DAX calculations, geographic drill-through navigation, and professional executive-level dashboard design.

### Business Objectives
- Monitor company-wide sales and profit metrics across product categories and time periods
- Analyze customer segmentation and purchasing behavior by geography
- Track production efficiency and identify operational bottlenecks
- Manage product returns and analyze root causes
- Evaluate product profitability and identify underperforming SKUs
- Provide KPIs dashboard with drill-down capabilities
- Visualize geographic sales distribution with interactive exploration

---

## 🎯 Key Features

### Multi-Page Navigation System
- **KPIs Overview**: Executive dashboard with high-level business metrics
- **Products & Categories Analysis**: Product portfolio and profitability analysis
- **Sales Performance**: Comprehensive sales trends and margin analysis
- **Customers Analysis**: Customer segmentation and demographic insights
- **Returns Analysis**: Quality management and return root cause analysis
- **Production Analysis**: Manufacturing efficiency and machine utilization
- **Country Drill-Through**: Interactive regional sales deep-dive (USA example)

### Advanced Interactive Elements
- **Geographic Drill-Through**: Click on map locations to drill into country-level detail pages
- **Multi-Year Analysis**: Year filters (2015-2017) across all pages
- **Time Period Selection**: Toggle between Year, Quarter, and Month views
- **Dynamic Slicers**: Country/region selection with cascading filters
- **Cross-page Navigation**: Seamless movement between related analyses

### Professional Design
- **Consistent Branding**: Adventure Works logo with cohesive orange/teal color scheme
- **Modern UI**: Rounded corners, shadow effects, and clean white space
- **Visual Hierarchy**: Icon-enhanced KPI cards with clear prioritization
- **Data-Driven Design**: Every element serves analytical purpose

---

## 📈 Dashboard Pages Breakdown

### 1️⃣ KPIs Overview
**Purpose**: Executive summary landing page with key business health indicators

**Key Metrics**:
- Total Sales: 24.91M
- Total Profit: 10.46M
- Average Margin %: 54%
- Number of Orders: 25K

**Features**:
- Prominent KPI cards with icons
- Quick navigation to detailed analysis pages
- Adventure Works branding and bicycle theme
- Clean, minimal design for executive consumption
---

### 2️⃣ Products & Categories Analysis
**Purpose**: Deep-dive into product portfolio, pricing, and profitability

**Key Metrics**:
- Total Products: 293
- Average Price: 714.44
- Total Sales: 24,514,586.82
- Most Sold Category: Bikes (23,642,495.10)

**Visualizations**:
- **Sales by Category and Subcategory**: Sunburst chart showing hierarchical breakdown
  - Bikes (primary): Road Bikes (11,287,182.69), Mountain Bikes (8,583,747.75)
  - Accessories: 906,673.11
  - Clothing: 365,418.62
- **Top 5 Underperforming Products**: Horizontal bar chart identifying problem SKUs
  - Mountain-100 Silver variants leading returns/underperformance
- **Top 10 Highest Cost Products**: Cost range from 388K to 670K
- **Top 10 Profiting Products**: Fender Set - Mountain leads (54.49K profit)

**Key Insights**:
- Bikes category represents 95% of total sales
- Road Bikes and Mountain Bikes are the revenue engines
- Accessories and Clothing are niche segments with growth potential
- High-margin specialty products driving profitability
- Mountain Tire Tube and Patch Kits show strong profit performance

**Interactive Features**: Year filters (2015-2017), Country and City selection buttons

---

### 3️⃣ Sales Performance
**Purpose**: Track sales trends, margins, and geographic performance

**Key Metrics**:
- Total Sales: 24.91M
- Total Cost: 14.46M
- Total Profit: 10.46M
- Average Yearly Sales: 8.30M
- Total Sold Qty: 84K
- **Profit Margin: 54.3%**

**Visualizations**:
- **Total Sales by Period**: Line chart showing sales progression over months or years or quarter according to user choice (made by field parameters)
- **Margin Relative to Sales**: Gauge chart showing 54.3% consistent profit margin
- **Sales by Locations**: Geographic map with bubble sizes representing sales volume
- **Quarterly/Monthly Performance Table**: Detailed year-over-year comparisons with variance indicators

**Key Insights**:
- Strong 54% profit margin demonstrates pricing power
- Consistent performance across 2015-2017 despite market variations
- Multiple geographic markets providing revenue diversification
- Monthly variance indicates opportunity for demand forecasting

**Time Period Analysis**:
- 2015: 6.4M sales baseline
- 2016: 9.3M sales (+45% growth)
- 2017: 9.1M sales (plateau phase)

---

### 4️⃣ Customers Analysis
**Purpose**: Understand customer base, demographics, and purchasing patterns

**Key Metrics**:
- Total Customers: 18K
- Average Sales per Customer: 1.37K
- Average Orders per Customer: 1.39
- Gender Distribution: 49% M / 50.2% F / 0.72% NA

**Visualizations**:
- **Customers Distribution over Countries**: Bar chart ranking markets
  - United States: 1.46K customers (leading market)
  - Australia: 1.38K customers (strong secondary market)
  - United Kingdom: 0.54K
  - Germany: 0.46K
  - France: 0.45K
  - Canada: 0.28K
- **Customers Educational Level**: Donut chart segmentation
  - Bachelors: 28.99% (largest segment)
  - Partial College: 27.36%
  - High School: 17.86%
  - Graduate Degree: 17.22%
  - Partial High School: 8.57%
- **Customers Count Per Time**: Line chart showing seasonal customer acquisition
- **Genders Distribution**: Pie chart showing nearly balanced male/female split

**Key Insights**:
- Geographic concentration in US/Australia suggests English-speaking market focus
- Educated customer base (95% with college+ education)
- Strong seasonal purchasing pattern correlating with outdoor season
- Nearly gender-balanced customer base
- Average customer lifetime value: 1.37K, indicating mid-market positioning

**Interactive Features**: Year/Quarter/Month time period selection, Country filter buttons (field parameters too)

---

### 5️⃣ Returns Analysis
**Purpose**: Manage product quality and understand return root causes

**Key Metrics**:
- Total Returns: 2K transactions
- Total Returned Products: 124 unique SKUs
- Sum of ReturnQuantity: 2K units

**Visualizations**:
- **Returns by Country**: Treemap showing geographic return distribution
  - United States: 624 returns (largest volume which is logic as it is the leading market)
  - Australia: 400 returns
  - Canada: 234 returns
  - United Kingdom: 204 returns
  - France: 186 returns
  - Germany: 161 returns
- **Most Common Return Reasons**: Donut chart analyzing root causes
  - Size not correct: 43.23% (dominant issue - fit/sizing problem)
  - Color variation: 27.75% (quality/expectation mismatch)
  - Broken part: 15.26% (defect)
  - Have a hole: 13.76% (damage)
- **Most Returned 10 Products**: Combo bar/line chart identifying problem SKUs
  - Sport-100 Helmets (various colors): 34-35 returns each
  - Fender Set - Mountain: 22 returns
  - Mountain Bottle Cage: 20 returns
  - Road Tire Tube: 17-18 returns
  - Peak return product: Mountain Tire (149 units - likely aggregated)
- **Returned Products by Year**: Line chart showing trend
  - 2015: 28 returns (baseline)
  - 2016: 409 returns (+1361% increase)
  - 2017: 486 returns (+19% continued growth)

**Key Insights**:
- Size/fit is the primary return driver (actionable through better size guides)
- USA market generates disproportionate returns (31% of total)
- Helmet and tire products have recurring quality issues
- Significant increase in returns 2015-2016 (possible quality spike)
- Color variation returns suggest product photography/description issues

**Quality Management Implications**: Recommend improved size guidance, helmet QC process review, and color accuracy in product listings

---

### 6️⃣ Production Analysis
**Purpose**: Monitor manufacturing efficiency and identify operational bottlenecks

**Key Metrics**:
- Total Lots: 38 production batches
- Average Lot Duration: 1.82 days
- Most Used Machine: Machine3
- Total Produced Qty: 100M units
- **Target Achievement: 79.17%**

**Visualizations**:
- **Lots with the Longest Duration**: Bar chart showing production lot processing times
- **Machines Contribution in Production**: Stacked bar chart showing machine utilization
  - Machine1: 451 units (16 contribution units shown), 8 articles
  - Machine2: 471 units (highest volume)
  - Machine3: Highest demonstrated contribution
  - Shows relative workload distribution across machinery
- **Production Qty Target Achievement**: Pie chart
  - Achieved: 79.17% (core target met)
  - Not Achieved: 20.83% (gap analysis opportunity)
- **Lots for each Downtime**: Bar chart identifying causes
  - Feeding station and machine head: 11 occurrences (top issue)
  - Material Shortage: 6 occurrences
  - Blow Head: 5 occurrences
  - Changeover: 5 occurrences

**Key Insights**:
- Production target achievement at 79% indicates opportunity for improvement
- Feeding station and Machine Head are equal top downtime causes
- Machine2 carries highest production volume
- Consistent lot duration (3.0-3.9 days) shows stable process control
- Material shortage appears occasionally, suggesting inventory management opportunity

**Operational Recommendations**:
- Investigate Feeding station reliability (critical bottleneck)
- Review Machine Head maintenance schedule
- Implement Material Planning to reduce shortage-related downtime
- Target 85%+ production achievement through downtime reduction

---

### 7️⃣ Country Drill-Through: Sales Analysis for United States
**Purpose**: Interactive drill-down page providing country-level detailed sales analysis

**Key Metrics** (USA Specific):
- Total Sales: 7.94M (32% of total company sales)
- Total Cost: 4.57M
- Total Profit: 3.36M (42% of total company profit)
- Average Yearly Sales: 2.65M
- Total Sold Qty: 30K
- **Profit Margin: 42.3%** (lower than company average of 54%)

**Visualizations**:
- **Most Sold 10 Products by Quantity**: Horizontal bar chart
  - Water Bottle - 30 oz: 3.0K units (dominant product)
  - Mountain Tire Tube: 2.4K units
  - Patch Kit/8 Patches: 2.1K units
  - Fender Set - Mountain: 1.8K units
  - Mountain Bottle Cage: 1.5K units
  - Shows clear product preference differences vs company average
- **Sales by Regions**: Stacked bar chart showing USA regional breakdown
  - Southwest: 4.8M (dominant region - 60% of USA sales)
  - Northwest: 3.1M (secondary market)
  - Southeast, Northeast, Central: Smaller volumes
  - Clear geographic opportunity in Southeast/Central regions
- **Customers Count Over Time**: Line area chart with seasonal pattern

**Drill-Through Feature Value**: Allows executives to click on a country on the geographic map from Sales Performance page and instantly see country-specific analysis

---

## 🛠️ Technical Implementation

### Data Model
- **Fact Tables**: Sales, Production
- **Dimension Tables**: Products, Orders, Customers, Date, Terroteries (Countries/Regions)
- **Date Table**: Complete date hierarchy for time intelligence (years, quarters, months)

### DAX Measures (Demonstrated)
- Total Sales and Sales YTD calculations
- Total Cost and Cost YTD
- Total Profit (Sales - Cost) with margin percentage
- Average Sales per Customer
- Average Orders per Customer
- Return rate by product/reason
- Production achievement percentage
- Year-over-Year variance (with trend indicators)
- Ranked product lists (Top N filtering)
- Geographic-based calculations for drill-through

### Advanced Features
- **Drill-Through Pages**: Geographic map click → Country detail page navigation
- **Time Intelligence**: Year/Quarter/Month filtering with comparative analysis using filed parameters
- **Conditional Formatting**: Variance indicators (up/down arrows) in tables
- **Dynamic Filtering**: Cascading filters between Country/Region selection

### Visualizations Used
- KPI Cards with custom icons and formatting
- Sunburst chart (hierarchical product data)
- Bar charts (horizontal and vertical)
- Line and area charts (trends and time series)
- Pie and donut charts (distribution)
- Geographic maps with bubble sizing
- Treemaps (hierarchical return distribution)
- Combination charts (bar + line for trend + quantity)
- Data tables with conditional formatting
- Gauges (margin percentage)

### Design Principles Applied
- Consistent Adventure Works branding (bicycle logo, orange/teal theme)
- Rounded corners for modern aesthetic
- Strategic use of color for emphasis
- Logical flow from overview → detail
---

## 📸 Screenshots & Repository Structure

All seven dashboards included as high-quality screenshots:

1. `overview.jpg` - KPIs Overview executive dashboard
2. `products-categories-analysis.jpg` - Product portfolio and profitability
3. `sales-analysis.jpg` - Sales performance and trends
4. `customers-analysis.jpg` - Customer segmentation and behavior
5. `returns-analysis.jpg` - Quality management and returns analysis
6. `production-analysis.jpg` - Manufacturing efficiency tracking
7. `country-drill-through.jpg` - drill-through detail page example

**Repository Structure**:  

data_bikes_dashboard/
│
├─── overview.jpg  

│── products-categories-analysis.jpg  

│── sales-analysis.jpg  

│── customers-analysis.jpg  

│── returns-analysis.jpg  

│── production-analysis.jpg  

│── country-drill-through.jpg  
└── README.md

---
## 💡 Business Impact & Strategic Insights

### Sales & Revenue Insights
- Total company revenue of 24.91M with strong 54% profit margin
- Bikes category dominance (95% of sales) represents concentration risk
- USA market leads (32% of total sales) with Southwest region as strongest performer
- Year-over-year growth 2015-2016 (+45%) plateaued in 2017, suggesting market

### Customer & Market Insights
- 18K customers providing diversified revenue base
- Educated customer demographic (95% college+) enables premium positioning
- Geographic concentration in English-speaking markets suggests expansion opportunity in other regions
- Nearly balanced gender split indicates universal product appeal

### Product & Profitability Insights
- Mountain and Road Bikes drive profitability despite similar unit economics
- Accessories (golf helmets, tubes, cages) show strong unit margins
- Water Bottle (30 oz) leads by volume, especially in USA market
- Top 10 products concentrated in low-cost, high-volume categories

### Quality & Operations Insights
- 2K returns from 25K orders (8% return rate) indicates quality concerns
- Size/fit issues (43%) are preventable through improved product information
- Production target achievement at 79% leaves 21% efficiency gap
- Equipment downtime primarily driven by two machines (Feeding station, Machine Head)

### Strategic Recommendations
1. **Diversify Product Mix**: Reduce bikes category dependency, grow accessories/clothing
2. **Geographic Expansion**: Enter non-English speaking markets to leverage Adventure Works brand
3. **Quality Improvement**: Focus on sizing accuracy and helmet defect rates
4. **Production Optimization**: Target 85%+ achievement through maintenance and process improvements
5. **USA Market Growth**: Southeast/Central regions underperform vs Southwest, investigate barriers

---

## 🎓 Skills Demonstrated

### Power BI Advanced Competencies
- ✅ Multi-page enterprise dashboard design
- ✅ Complex DAX measure development (YTD, variance, rankings)
- ✅ Advanced data modeling with multiple fact tables
- ✅ Geographic/map visualizations with bubble sizing
- ✅ Drill-through page navigation and filtering
- ✅ Time intelligence and date hierarchy implementation

### Business Intelligence Skills
- ✅ Executive dashboard creation and KPI definition
- ✅ Cross-functional analysis (sales, operations, quality)
- ✅ Root cause analysis (returns, production efficiency)
- ✅ Variance analysis and trend identification
- ✅ Geographic and temporal analysis
- ✅ Production metrics and operational BI

### Design & User Experience
- ✅ Consistent branding and color theory
- ✅ User navigation and drill-down capabilities
- ✅ Professional presentation standards
- ✅ Accessibility and clarity principles

---

## 🔍 Data Sources & Database

This project uses the **Adventure Works Sample Database**, a comprehensive sample dataset from Microsoft representing a global manufacturing company. Key tables include:

- **Sales Tables**: Sales, Orders
- **Product Tables**: Products, Categories, Subcategories
- **Customer Table**: Customers, Customer Demographics, Customer Addresses
- **Production Tables**: Production_lot, Downtimes_island, Machines_island
- **Returns Table**: Returns, Return Reasons
- **Terroteries Table**: Countries, States, Cities
- **Employee Table**: Sales Staff organizational structure
- **Date Dimension**: Complete date hierarchy

---

## 👨‍💻 About This Project

This comprehensive Power BI dashboard portfolio demonstrates enterprise-level business intelligence capabilities. The project showcases complete BI development from data modeling through interactive dashboard delivery, featuring advanced techniques like drill-through navigation, complex time intelligence, and multi-dimensional analysis.

### Technologies & Tools Used
- **Power BI Desktop**: Dashboard and report development
- **DAX**: Advanced measure calculations and time intelligence
- **Power Query**: Data transformation and cleansing
- **SQL (Implied)**: Data source management
- **Adventure Works Database**: Comprehensive sample data

---

## 📧 Contact & Professional Links
Feel free to reach out to discuss this project or potential collaborations!  

**LinkedIn**: [MyLinkedIn](https://www.linkedin.com/in/hossam-badawy)  

**Email**: hossam.mousa779@gmail.com 

---

## 📝 License

This project is available for educational and portfolio purposes. The Adventure Works database is a Microsoft sample database available for public use under the sample database license.

