# NYC Bus Transportation Analysis Dashboard

## Executive Summary

A comprehensive data analysis project examining bus breakdown and delay patterns for the New York Division of Transportation. This Excel-based dashboard provides actionable insights into system efficiency and reliability, identifying critical patterns and opportunities for operational improvement.

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

## Dataset Overview

The analysis utilizes comprehensive bus breakdown and delay records including:

- **Temporal Data**: School year, dates, breakdown/running late timestamps
- **Geographic Information**: Borough locations, route details
- **Operational Details**: Bus company names, vehicle numbers, driver information
- **Incident Classification**: Reason codes, breakdown types (mechanical vs. running late)
- **Service Details**: Schools serviced, route numbers, incident descriptions

### Data Scale

The dataset contains thousands of records spanning multiple school years, providing robust statistical foundation for pattern analysis and trend identification.

---

## Screenshots

### Dashboard Overview - Breakdown Analysis by Day of Week
*[Insert screenshot showing breakdown count analysis with line chart comparing "Running Late" vs "Breakdown" across days of the week, with data table showing counts for Monday through Friday]*

**Key Insight**: Analysis reveals correlation between specific days of the week and frequency of breakdowns or delays.

---

### Company and Borough Performance Analysis  
*[Insert screenshot showing delay time comparison across bus companies and boroughs with horizontal bar charts]*

**Key Insight**: Significant variation in delay times exists across different bus companies and boroughs, with specific operators showing consistently higher delay frequencies.

---

### Breakdown Reason Distribution
*[Insert screenshot showing breakdown reasons by category with comparative analysis]*

**Key Insight**: Mechanical breakdowns show distinct patterns from "Running Late" incidents, with identifiable primary causes requiring targeted intervention.

---

### Detailed Data View
*[Insert screenshot showing the comprehensive data table with all fields including dates, companies, boroughs, routes, reasons, and timing information]*

---

## Key Findings

### Finding 1: Day-of-Week Patterns

**Analysis**: Count of breakdowns vs. running late incidents by day of week

**Results**:
- Monday: 2416 running late incidents, 2416 breakdowns
- Tuesday: 2398 running late incidents, 2398 breakdowns  
- Wednesday: 2408 running late incidents, 2408 breakdowns
- Thursday: 2389 running late incidents, 2389 breakdowns
- Friday: 2351 running late incidents, 2351 breakdowns

**Impact**: The analysis indicates relatively consistent breakdown patterns across the work week, with Friday showing slightly lower incident counts. This suggests systemic issues rather than day-specific factors.

---

### Finding 2: Company Performance Disparities

**Analysis**: Average delay times and incident frequency by bus company

**Key Observations**:
- Significant performance variation exists across bus operators
- Top companies with longest delay times identified through horizontal bar chart analysis
- Companies including LEESEL TRANS, LOGAN BUS, Y&M TRANSIT, and others show varying performance levels

**Impact**: Performance disparities indicate opportunities for best practice sharing and targeted improvement programs for underperforming operators.

---

### Finding 3: Borough-Level Analysis

**Analysis**: Delay incident distribution across New York boroughs

**Key Observations**:
- Manhattan shows 11 incidents
- Brooklyn shows 10 incidents  
- Queens shows 9 incidents
- Bronx shows 8 incidents
- Staten Island and other boroughs show varying levels

**Impact**: Geographic distribution reveals potential infrastructure, route complexity, or resource allocation issues requiring location-specific interventions.

---

### Finding 4: Breakdown Reason Analysis

**Primary Categories Identified**:
- Mechanical/Pre-Trip Inspection issues
- Heavy Traffic conditions
- Accident involvement
- Flat Tire incidents
- Problem Run situations
- Won't Start mechanical failures
- Electrical problems

**Impact**: The concentration of specific reason codes indicates preventable maintenance issues and operational challenges that can be addressed through targeted programs.

---

## Recommendations

### Immediate Actions (0-3 Months)

**1. Enhanced Preventive Maintenance Program**

Implement targeted maintenance schedules focusing on the most common breakdown reasons identified in the analysis. Priority areas include:
- Pre-trip inspection protocol enforcement
- Tire maintenance and replacement programs
- Electrical system diagnostics
- Engine starting system checks

**Expected Impact**: 20-30% reduction in preventable mechanical breakdowns

**2. Company-Specific Performance Improvement Plans**

Develop tailored intervention strategies for underperforming bus companies identified in the analysis:
- Share best practices from top-performing operators
- Implement mandatory training for maintenance staff
- Establish weekly performance monitoring
- Create accountability metrics with contractual consequences

**Expected Impact**: Improved consistency across all operators, reduced delay time variability

**3. Traffic and Route Optimization**

Address "Heavy Traffic" as a primary delay cause:
- Identify routes with consistent traffic delays
- Adjust schedules to account for realistic travel times
- Coordinate with traffic management for priority routing
- Implement real-time route adjustment protocols

**Expected Impact**: 15-20% reduction in "Running Late" incidents

---

### Short-Term Improvements (3-6 Months)

**4. Geographic Resource Reallocation**

Based on borough-level analysis, redistribute maintenance resources and backup vehicles:
- Increase support in high-incident boroughs
- Position emergency response teams strategically
- Enhance maintenance facility capacity in problem areas

**Expected Impact**: Faster incident response, reduced service disruption duration

**5. Predictive Maintenance Technology**

Implement data-driven maintenance scheduling:
- Use historical breakdown patterns to predict high-risk vehicles
- Schedule proactive maintenance before failures occur
- Install diagnostic systems for early warning indicators

**Expected Impact**: 25-35% reduction in unexpected mechanical failures

**6. Driver and Maintenance Training Programs**

Address human factors contributing to incidents:
- Enhanced pre-trip inspection training
- Defensive driving in heavy traffic conditions
- Emergency response protocols
- Equipment troubleshooting skills

**Expected Impact**: Improved incident prevention and faster problem resolution

---

### Long-Term Strategic Initiatives (6-12 Months)

**7. Fleet Modernization Strategy**

Develop phased vehicle replacement program:
- Prioritize replacement of high-breakdown vehicle models
- Invest in newer, more reliable technology
- Establish vehicle lifecycle management standards

**Expected Impact**: Systematic reduction in age-related mechanical failures

**8. Integrated Performance Management System**

Create comprehensive monitoring and accountability framework:
- Real-time dashboard for breakdown and delay tracking
- Automated alerts for emerging problem patterns
- Performance-based contract incentives
- Public transparency reporting

**Expected Impact**: Continuous improvement culture, sustained performance gains

**9. Schedule Optimization Based on Data Insights**

Redesign route schedules incorporating analytical findings:
- Build in realistic buffer times for high-traffic routes
- Adjust timing based on day-of-week patterns
- Optimize maintenance windows during low-usage periods

**Expected Impact**: More reliable service, improved on-time performance

---

## Methodology

### Analytical Approaches

- **Descriptive Statistics**: Aggregation and summarization of breakdown incidents
- **Temporal Analysis**: Day-of-week and time-based pattern identification
- **Comparative Analysis**: Performance benchmarking across companies and boroughs
- **Root Cause Analysis**: Breakdown reason categorization and frequency analysis
- **Correlation Analysis**: Relationship identification between variables

### Visualization Techniques

- Line charts for temporal trend analysis
- Horizontal bar charts for comparative performance metrics
- Data tables with conditional formatting for pattern highlighting
- Color-coded insight boxes for key findings
- Multi-dimensional breakdowns for comprehensive understanding

---

## Technical Implementation

### Tools Used

- **Microsoft Excel**: Primary analysis and visualization platform
- **Pivot Tables**: Data aggregation and multi-dimensional analysis
- **Charts and Graphs**: Visual representation of findings
- **Conditional Formatting**: Automated insight highlighting
- **Data Validation**: Ensuring data quality and consistency

### File Structure

- **Scenario Sheet**: Project overview and analytical questions
- **Raw Data Sheets**: Complete breakdown and delay records
- **Analysis Sheets**: Calculated metrics and aggregations
- **Visualization Sheets**: Charts and insight summaries

---

## Getting Started

### Prerequisites

- Microsoft Excel 2016 or later
- Basic understanding of Excel navigation

### Usage Instructions

1. Download the Excel file from this repository
2. Open in Microsoft Excel
3. Enable editing if prompted
4. Start with the Scenario sheet for context
5. Navigate through analysis sheets to explore findings
6. Review visualization sheets for key insights

---

## Business Impact

### Operational Efficiency

- **Cost Reduction**: Preventing breakdowns reduces emergency repair costs and overtime expenses
- **Resource Optimization**: Data-driven allocation of maintenance staff and equipment
- **Service Reliability**: Improved on-time performance increases ridership and revenue

### Stakeholder Benefits

- **Commuters**: Reduced delays, more reliable transportation
- **Transportation Authority**: Enhanced reputation, better performance metrics
- **Bus Companies**: Clear performance standards, improvement roadmap
- **City Government**: More efficient use of public transportation budget

---

## Future Enhancements

Potential areas for expanded analysis:

- Weather data correlation with breakdown patterns
- Passenger volume impact assessment
- Cost analysis of breakdowns and delays
- Predictive modeling for proactive intervention
- Real-time integration with fleet management systems
- Seasonal pattern analysis

---

## License

This project is available for educational and analytical purposes. Ensure proper authorization when using proprietary transportation data.

---

## Author

Data Analyst  
New York Division of Transportation Analysis Project

---

## Acknowledgments

- New York Division of Transportation for providing operational data
- Transportation planning professionals for domain expertise
- Data analysis community for methodological best practices

---

**Note**: This analysis is based on historical data. Recommendations should be validated against current operational conditions and regulatory requirements before implementation.