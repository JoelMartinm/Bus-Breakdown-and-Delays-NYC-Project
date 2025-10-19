# NYC Bus Transportation Analysis Dashboard

## Executive Summary

A comprehensive data analysis project examining bus breakdown and delay patterns for the New York Division of Transportation. This Excel-based dashboard provides actionable insights into system efficiency and reliability through rigorous data cleaning, transformation, and multi-dimensional analysis.

---

## Project Overview

### Background

The New York Division of Transportation has been experiencing significant bus breakdowns and delays, causing inconvenience to commuters and straining public transportation resources. This project analyzes breakdown and delay data to identify patterns, root causes, and actionable solutions.

### Scenario

You've been hired by the New York Division of Transportation as a Data Analyst with the primary goal of improving the efficiency and reliability of the city's bus transportation system. The city has been experiencing a significant number of bus breakdowns and delays, which has been causing inconvenience to commuters and straining the city's public transportation resources.

Your task is to analyze the provided data to identify patterns and factors that contribute to these breakdowns and delays.

### Key Questions

1. What are the most common reasons for delays and breakdowns?
2. How do delay times vary by bus company and borough?
3. Is there a correlation between specific days of the week and the frequency of breakdowns or delays?

---

## Data Cleaning and Preparation

### Importance of Data Quality

Reliable analysis begins with clean, consistent, and well-structured data. The raw dataset contained formatting errors, missing values, and inconsistencies that required careful cleaning to ensure analytical accuracy.

### Screenshots: Before and After

**Uncleaned Data**

![Uncleaned Data Screenshot](screenshot-placeholder-uncleaned.png)

The original dataset exhibited numerous data quality issues that would have compromised analytical integrity.

**Cleaned Data**

![Cleaned Data Screenshot](screenshot-placeholder-cleaned.png)

After comprehensive cleaning, the dataset became fully structured and analysis-ready.

### Key Issues Identified

- **Inconsistent date, numeric, and text formats** - Date fields displayed as serial numbers and mixed formats
- **Unstandardized field names and categorical values** - Company names, boroughs, and reason codes lacked consistency
- **Missing or incomplete data entries** - Gaps in critical fields affecting completeness
- **Structural disorganization** - Poor column organization affecting readability and pivot analysis

### Cleaning Steps

**1. Standardization**
- Unified date formats to consistent MM/DD/YYYY structure
- Standardized number formats for vehicle IDs and route numbers
- Normalized categorical fields (company names, boroughs, reason codes)

**2. Normalization**
- Ensured consistency in company names (removed extra spaces, unified capitalization)
- Standardized borough identifiers (Manhattan, Brooklyn, Queens, Bronx, Staten Island)
- Cleaned reason descriptions for categorical grouping

**3. Data Type Conversion**
- Converted text-based numbers to proper numeric format
- Transformed date serial numbers into recognizable date formats
- Ensured Boolean fields displayed consistently

**4. Structural Reorganization**
- Added descriptive column headers for clarity
- Logically arranged columns by category (temporal, geographic, operational, incident)
- Created proper table structure for pivot table functionality

**5. Validation**
- Verified data accuracy across all fields
- Cross-checked geographic identifiers against known boroughs
- Corrected anomalies and outliers

**6. Handling Missing Data**
- Identified patterns in missing values
- Applied appropriate strategies (removal or documentation)
- Ensured data gaps did not skew results

### Results

- Clean, structured, and analysis-ready dataset
- Consistent field formats and naming conventions
- Zero formatting errors in key analytical columns
- Seamless compatibility with Excel formulas, charts, and pivot tables

### Impact

The cleaned dataset enhanced **accuracy**, **reproducibility**, and **efficiency** of analysis — ensuring that all insights derived are reliable, interpretable, and ready for presentation or forecasting.

---

## Analysis and Key Findings

### Question 1: What are the most common reasons for delays and breakdowns?

#### Breakdown Reasons Analysis

![Breakdown Reasons Chart](https://github.com/user-attachments/assets/92f86b6f-a14d-4504-9995-540d3571a693)

**Key Finding**: The majority of breakdowns are occurring due to **Mechanical Problems** or **"Won't Start"** issues, which also appear to be mechanical in nature.

**Breakdown Distribution**:
- Mechanical/Pre-Trip Inspection issues represent the dominant cause
- "Won't Start" problems indicate systematic vehicle maintenance gaps
- Preventable mechanical failures constitute the largest opportunity for improvement

**Implications**:
- Maintenance protocols require immediate review and enhancement
- Vehicle inspection procedures need strengthening
- Predictive maintenance programs could prevent majority of breakdowns

**Recommendations**:

1. **Comprehensive Preventive Maintenance Overhaul** - Implement rigorous pre-trip inspection protocols with mandatory digital checklists, focus maintenance efforts on identified failure points such as starting systems and mechanical components, and create vehicle-specific maintenance plans based on historical breakdown data to address the mechanical problems and "Won't Start" issues that dominate breakdown causes.

2. **Predictive Maintenance Technology** - Install diagnostic systems that provide early warning of mechanical issues, use historical data to identify high-risk vehicles requiring immediate attention, and schedule proactive component replacements before failures occur to transition from reactive to proactive maintenance.

3. **Fleet Modernization Program** - Identify and prioritize replacement of highest-breakdown vehicles, particularly those with chronic "Won't Start" issues, invest in newer vehicles with better reliability records, and create a systematic replacement schedule based on breakdown frequency patterns.

4. **Enhanced Weekend Maintenance Quality Control** - Establish comprehensive quality assurance checks on all weekend maintenance work with supervisor sign-offs, create mandatory Monday morning verification inspections, and track weekend maintenance completion rates to address the root cause of Monday breakdown spikes.

5. **Mid-Week Preventive Maintenance Schedule** - Schedule strategic mid-week preventive maintenance to address the progressive decline in reliability throughout the week, catching potential issues before they result in end-of-week breakdowns.

---

#### Delay Reasons Analysis

![Delay Reasons Chart](https://github.com/user-attachments/assets/ca2ea521-6375-4bb5-85a3-a16882c27cd7)

**Key Finding**: Overwhelmingly, the main cause of delays is **Heavy Traffic**.

**Delay Distribution**:
- Traffic congestion is the primary operational challenge
- Environmental factors beyond direct mechanical control dominate delays
- Route timing and scheduling optimization represent key improvement areas

**Implications**:
- Schedule adjustments needed to account for realistic traffic patterns
- Alternative routing strategies should be explored during peak hours
- Coordination with city traffic management is essential

**Recommendations**:

1. **Traffic-Adaptive Schedule Optimization** - Redesign schedules with realistic buffer times for high-traffic routes based on historical delay data, create Monday-specific schedules that account for week-start traffic surges, and build Friday's lower delay patterns into capacity planning.

2. **Dynamic Routing Implementation** - Implement dynamic routing capabilities that allow real-time traffic adjustments, enabling drivers and dispatchers to respond to current conditions rather than following fixed routes during congestion.

3. **Traffic Congestion Mitigation Partnership** - Partner with NYC Department of Transportation for dedicated bus lanes in high-congestion areas, coordinated traffic signal timing that provides bus priority, and exploration of alternative routing during peak congestion periods.

4. **Monday-Specific Traffic Management** - Create enhanced Monday-specific traffic management coordination with city agencies to anticipate and mitigate the week-start congestion patterns that cause delay spikes.

5. **Resource Redistribution Based on Day Patterns** - Build Friday's demonstrated lower delay patterns into capacity planning by redistributing some resources to Monday operations when demand and incident rates are highest.

---

### Question 2: How do delay times vary by bus company and borough?

#### Company Performance Analysis

![Top 10 Companies by Delay Time](https://github.com/user-attachments/assets/586495ce-401d-467b-9197-b46c0ff2f98a)

**Key Finding**: The chart displays the **10 bus companies that have the highest average delay or breakdown time**.

**Performance Insights**:
- Significant variation exists across bus operators
- Top delay-prone companies require immediate performance intervention
- Performance disparities suggest operational practice differences

**Implications**:
- Underperforming companies need targeted improvement plans
- Best practices from reliable operators should be shared system-wide
- Contract performance metrics should incorporate these findings

**Recommendations**:

Tackle company performance disparities through a comprehensive performance improvement program. Conduct detailed operational audits of the top 10 highest-delay companies to identify specific operational deficiencies and root causes of poor performance. Implement systematic best practice sharing from reliable operators through structured knowledge transfer programs, site visits, and joint training sessions. Create mandatory performance improvement plans with measurable targets, clear timelines, and milestone checkpoints for underperforming companies. Establish financial incentives for demonstrated performance improvement and penalties for continued poor performance, linking contract renewals and payment structures to reliability metrics. Require weekly performance reviews with corrective action reporting, ensuring ongoing accountability and transparent progress tracking across all operators.

---

#### Borough Performance Analysis

![Borough Delay Times](https://github.com/user-attachments/assets/95e1e062-345d-4c9b-aa55-63ac077ad67b)

**Key Finding**: The boroughs with the highest delay times are the **main areas of NYC**. These are the areas with the highest concentration of people and vehicles, which would account for the longer delays.

**Geographic Insights**:
- Manhattan, Brooklyn, and Queens show elevated delay frequencies
- Population density and traffic congestion directly correlate with delays
- Urban complexity creates operational challenges

**Implications**:
- High-density areas require additional resources and backup vehicles
- Schedule buffers should be larger for congested borough routes
- Geographic-specific strategies needed for dense urban areas

**Recommendations**:

Reallocate resources geographically based on borough-specific delay patterns. Position additional backup buses and spare vehicles in Manhattan, Brooklyn, and Queens where the highest delay times and incident frequencies occur. Increase maintenance facility capacity and establish satellite maintenance locations in high-incident boroughs to enable faster response times and reduce service disruption duration. Deploy dedicated rapid response teams strategically near the most congestion-prone areas within high-density boroughs, ensuring quick incident resolution. Allocate longer schedule buffers specifically for routes operating in dense urban areas, accounting for the higher probability of traffic delays and the complexity of navigating congested streets. Adjust resource distribution dynamically based on ongoing performance data to ensure the most challenged areas receive appropriate support.

---

### Question 3: Is there a correlation between specific days of the week and the frequency of breakdowns or delays?

#### Day-of-Week Delay Patterns

![Delay Frequency by Day](https://github.com/user-attachments/assets/1ea4d08e-a005-46c4-b9da-4fd9c6c8b885)

**Key Finding**: **Spike in delays on Monday** and a **decrease in delays on Fridays**. Since the majority of delays are caused by traffic, we can assume the decrease in delays on Friday are caused by less people going into work or driving on that day.

**Temporal Pattern**:
- Monday shows highest delay frequency (beginning-of-week traffic surge)
- Gradual decline through the week
- Friday shows notably lower delays (reduced commuter traffic)

**Implications**:
- Monday operations require additional resources and backup buses
- Schedule timing should reflect day-specific traffic patterns
- Friday capacity could potentially be redistributed to higher-demand days

**Recommendations**:

Address the Monday delay spike through enhanced Monday-specific operations and resource allocation. Increase Monday staffing levels across all functions including drivers, maintenance personnel, and dispatch coordinators to handle the elevated demand and incident frequency. Position additional backup vehicles specifically for Monday deployment, ensuring rapid replacement capability when delays or breakdowns occur. Create Monday-specific traffic management coordination with city agencies to anticipate and mitigate the week-start congestion patterns. Build Friday's demonstrated lower delay patterns into capacity planning by potentially redistributing some resources to Monday operations when demand and incident rates are highest, optimizing overall system efficiency across the week.

---

#### Day-of-Week Breakdown Patterns

![Breakdown Frequency by Day](https://github.com/user-attachments/assets/1de9576b-2080-4cf2-830b-7a61db490a6c)

**Key Finding**: There is a **gradual decrease in breakdowns throughout the week**. Higher percentage of breakdowns happening on Monday and decreases throughout the week.

**Breakdown Trend**:
- Monday experiences highest mechanical breakdown frequency
- Progressive decline from Monday through Friday
- Pattern suggests weekend maintenance effects wear off by week's end

**Implications**:
- Weekend maintenance quality should be reviewed and improved
- Mid-week preventive maintenance could reduce late-week reliability
- Monday vehicle inspections should be particularly thorough

**Recommendations**:

Implement enhanced weekend maintenance quality control to address the root cause of Monday breakdown spikes. Establish comprehensive quality assurance checks on all weekend maintenance work, requiring supervisor sign-offs on completed tasks to ensure accountability and thoroughness. Create mandatory Monday morning verification inspections that specifically check all weekend maintenance work before vehicles enter service, catching any issues before they cause on-route breakdowns. Track weekend maintenance completion rates, quality metrics, and correlation with Monday breakdown incidents to identify problematic patterns or facilities. Schedule strategic mid-week preventive maintenance to address the progressive decline in reliability throughout the week, catching potential issues before they result in Friday breakdowns. Review and enhance weekend maintenance protocols, staffing levels, and supervision to ensure consistent quality that prevents the observed Monday effect. Additionally, implement a real-time performance monitoring system with dashboards tracking breakdowns and delays by day of week, automated alerts when Monday metrics exceed established thresholds, and daily performance reports distributed to all companies, enabling rapid response to emerging patterns and fostering a culture of continuous improvement and accountability across the entire week.

---

## Summary of Key Findings

### Primary Insights

1. **Mechanical Issues Dominate Breakdowns**: Mechanical problems and "Won't Start" issues are the leading causes of breakdowns, indicating systematic maintenance gaps that are preventable through enhanced protocols.

2. **Traffic is the Main Delay Driver**: Heavy traffic overwhelmingly causes delays, requiring schedule optimization and coordination with city traffic management rather than just vehicle improvements.

3. **Significant Company Performance Variation**: The top 10 delay-prone companies show substantial performance disparities, presenting opportunities for best practice sharing and targeted interventions.

4. **Geography Matters**: High-density boroughs (Manhattan, Brooklyn, Queens) experience longer delays due to population concentration and traffic congestion, requiring location-specific resource allocation.

5. **Monday Effect is Real**: Both delays and breakdowns spike on Mondays and decline through the week, suggesting weekend maintenance effects and beginning-of-week traffic patterns require operational adjustments.

---

## Business Impact

### Operational Efficiency

**Cost Implications**
- Preventable mechanical breakdowns waste maintenance resources and increase emergency repair costs
- Traffic-related delays require additional buses and drivers to maintain schedule integrity
- Monday spikes create overtime expenses and resource strain

**Resource Utilization**
- Current maintenance practices not preventing recurring mechanical issues
- Geographic resource distribution not optimized for high-density areas
- Day-of-week patterns not reflected in resource allocation

**Service Reliability**
- Mechanical breakdowns and traffic delays erode public trust in the system
- Company performance variations create inconsistent rider experiences
- Peak Monday incidents strain system capacity and connections

### Stakeholder Impact

**Commuters**
- Unpredictable mechanical breakdowns disrupt schedules and plans
- Traffic-related delays compound commute times
- Monday incidents particularly affect week-start work and school attendance

**Transportation Authority**
- Reputation suffers from visible service disruptions
- Performance metrics below acceptable standards
- Political pressure increases with continued reliability issues

**Bus Companies**
- Underperforming companies face contract renewal risks
- Variation in performance creates competitive disadvantages
- Maintenance costs escalate with reactive rather than preventive approach

---

## Recommendations

Based on comprehensive analysis of breakdown patterns, delay causes, company performance, geographic distribution, and temporal trends, the following integrated recommendations provide actionable solutions to improve NYC bus transportation reliability. First, implement a comprehensive preventive maintenance overhaul focusing on the mechanical problems and "Won't Start" issues that dominate breakdown causes, including rigorous pre-trip inspection protocols, mid-week preventive maintenance scheduling to address Monday breakdown spikes, and quality control audits of weekend maintenance work to reduce the observed Monday effect. Second, address the overwhelming impact of heavy traffic on delays through traffic-adaptive schedule optimization, redesigning schedules with realistic buffer times for high-traffic routes, creating Monday-specific schedules that account for week-start traffic surges, implementing dynamic routing capabilities for real-time adjustments, and coordinating with NYC Department of Transportation for bus priority lanes in high-density boroughs like Manhattan, Brooklyn, and Queens. Third, tackle company performance disparities by conducting operational audits of the top 10 highest-delay companies, implementing best practice sharing from reliable operators, establishing performance improvement plans with measurable targets and financial incentives, and requiring weekly performance reviews with corrective action reporting. Fourth, reallocate resources geographically by positioning additional backup buses and maintenance capacity in high-density boroughs that experience disproportionate delays, deploying rapid response teams near congestion-prone areas, and allocating longer schedule buffers for dense urban routes. Fifth, enhance Monday operations specifically by increasing staffing levels, implementing enhanced Monday morning vehicle inspections, positioning additional backup vehicles for Monday deployment, and creating Monday-specific traffic management coordination to address the significant spike in both delays and breakdowns observed at the beginning of each week. Additionally, invest in predictive maintenance technology to transition from reactive to proactive maintenance by installing diagnostic systems that provide early warning of mechanical issues, using historical data to identify high-risk vehicles, and scheduling component replacements before failures occur. Accelerate fleet modernization by prioritizing replacement of highest-breakdown vehicles, particularly those with chronic "Won't Start" issues, and establishing systematic retirement schedules based on breakdown frequency data. Partner with city agencies for traffic congestion mitigation through dedicated bus lanes, coordinated traffic signal timing for bus priority, and exploration of alternative routing during peak congestion periods. Implement enhanced weekend maintenance quality control with supervisor sign-offs, Monday morning verification inspections, and completion rate tracking to address the root cause of Monday breakdown spikes. Finally, create a real-time performance monitoring system with dashboards tracking breakdowns and delays, automated alerts when metrics exceed thresholds, and daily performance reports to all companies, enabling rapid response to emerging patterns and fostering a culture of continuous improvement. These comprehensive, data-driven recommendations address the root causes identified in the analysis and provide measurable pathways to significant improvements in system reliability, operational efficiency, and rider satisfaction.

---

## Methodology

### Analytical Approaches

**Data Preparation**: Comprehensive cleaning and standardization transforming raw data into analysis-ready format

**Descriptive Statistics**: Aggregation and summarization across multiple dimensions (company, borough, day, reason)

**Temporal Analysis**: Day-of-week pattern identification revealing operational trends

**Comparative Analysis**: Performance benchmarking across companies and geographic areas

**Root Cause Analysis**: Breakdown and delay reason categorization identifying primary issues

**Visual Analytics**: Chart-based pattern recognition enabling intuitive insight discovery

### Visualization Techniques

- Horizontal bar charts for comparative performance metrics
- Line charts for day-of-week temporal patterns
- Category distribution charts for reason code analysis
- Color-coded data tables for pattern highlighting
- Integrated text insights explaining chart findings

---

## Technical Implementation

### Tools and Technologies

- **Microsoft Excel**: Primary analysis and visualization platform
- **Data Cleaning**: Formula-based standardization and manual validation
- **Pivot Tables**: Multi-dimensional data aggregation
- **Charts and Graphs**: Visual representation of findings
- **Conditional Formatting**: Pattern highlighting and insight emphasis
- **Data Validation**: Quality assurance and consistency checking

### Project Structure

- **Scenario Sheet**: Project context and analytical questions
- **Uncleaned Data Sheet**: Original raw data preserving data lineage
- **Cleaned Data Sheet**: Standardized, analysis-ready dataset
- **Analysis Sheets**: Pivot tables and calculated metrics
- **Visualization Sheets**: Charts with integrated insights
- **Dashboard Sheet**: Summary view of key findings

---

## Getting Started

### Prerequisites

- Microsoft Excel 2016 or later
- Basic understanding of Excel navigation
- Familiarity with pivot tables and charts recommended

### Installation and Usage

1. Download the `.xlsx` file from this repository
2. Open in Microsoft Excel
3. Enable editing and macros if prompted
4. Review the Scenario sheet for project context
5. Compare Uncleaned vs. Cleaned data sheets to understand data preparation
6. Navigate through analysis and visualization sheets
7. Explore the dashboard for summary insights

### File Navigation

- **Scenario**: Start here for project overview
- **Data Sheets**: Review cleaning transformation
- **Analysis**: Explore detailed breakdowns
- **Visualizations**: View charts and findings
- **Dashboard**: See summary of key insights

---

## Use Cases

This analysis framework supports:

- **Strategic Planning**: Long-term transportation system improvements
- **Resource Allocation**: Data-driven budget and staffing decisions
- **Performance Management**: Company accountability and improvement tracking
- **Operational Optimization**: Schedule and route adjustments
- **Maintenance Planning**: Preventive maintenance program design
- **Policy Development**: Transportation reliability standards
- **Contract Management**: Performance-based operator agreements

---

## Future Enhancements

Potential expansions to this analysis:

- **Weather Data Integration**: Correlation between weather conditions and incidents
- **Passenger Volume Analysis**: Impact of breakdowns on ridership and capacity
- **Cost-Benefit Analysis**: Financial quantification of improvement recommendations
- **Predictive Modeling**: Machine learning for breakdown forecasting
- **Real-Time Dashboard**: Live monitoring integrated with fleet management
- **Seasonal Analysis**: Year-round pattern identification
- **Route Complexity Scoring**: Analysis of route characteristics affecting reliability

---

## Contributing

Contributions to enhance this analysis are welcome:

- Additional visualizations or analytical perspectives
- Automation scripts for data refresh and analysis updates
- Integration with external data sources (weather, traffic, ridership)
- Advanced statistical modeling approaches
- Dashboard enhancements and interactive features

---

## License

This project is available for educational and analytical purposes. Ensure proper authorization when using proprietary transportation data.

---

## Author

Data Analyst  
New York Division of Transportation Analysis Project

---

## Acknowledgments

- New York Division of Transportation for providing comprehensive operational data
- Transportation planning professionals for domain expertise and validation
- Data analysis community for methodological guidance and best practices
- Excel user community for advanced analytical techniques

---

## Contact

For questions, suggestions, or collaboration opportunities regarding this analysis, please open an issue in this repository.

---

**Project Status**: Complete

**Last Updated**: 2024

**Data Period**: Multiple school years of NYC bus transportation records

---

**Note**: This analysis represents findings based on historical data. All recommendations should be validated against current operational conditions, regulatory requirements, and budget constraints before implementation. The data cleaning methodology described serves as a template for ongoing data quality management.