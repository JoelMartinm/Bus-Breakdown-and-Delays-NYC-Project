# NYC Bus Transportation Analysis

## Executive Summary

A comprehensive data analysis project examining bus breakdown and delay patterns for the New York Division of Transportation. This Excel project provides actionable insights into system efficiency and reliability through rigorous data cleaning, transformation, and multi-dimensional analysis.

---


### Background

The New York Division of Transportation has been experiencing significant bus breakdowns and delays, causing inconvenience to commuters and straining public transportation resources. This project analyzes breakdown and delay data to identify patterns, root causes, and actionable solutions.

### Scenario

The New York Division of Transportation has hired you as a Data Analyst with the primary goal of improving the efficiency and reliability of the city's bus transportation system. The city has been experiencing a significant number of bus breakdowns and delays, which have been causing inconvenience to commuters and straining the city's public transportation resources.

Your task is to analyze the provided data to identify patterns and factors that contribute to these breakdowns and delays.

### Key Questions

1. What are the most common reasons for delays and breakdowns?
2. How do delay times vary by bus company and borough?
3. Is there a correlation between specific days of the week and the frequency of breakdowns or delays?

---

## Data Cleaning and Preparation

### Importance of Data Quality
Reliable analysis begins with clean, consistent, and well-structured data. The raw dataset contained formatting errors, missing values, and inconsistencies that required careful cleaning to ensure analytical accuracy.

### Key Issues Identified
- Inconsistent date, numeric, and text formats  
- Unstandardized field names and categorical values  
- Missing or incomplete data entries  
- Structural disorganization affecting readability and pivot analysis  

### Cleaning Steps
1. **Standardization** – Unified date and number formats, and normalized categorical fields.  
2. **Normalization** – Ensured consistency in names (e.g., company, region) and removed extra spaces.  
3. **Data Type Conversion** – Converted text-based numbers and dates into correct data types.  
4. **Structural Reorganization** – Added descriptive headers and logically arranged columns.  
5. **Validation** – Verified data accuracy, cross-checked identifiers, and corrected anomalies.  
6. **Handling Missing Data** – Replaced null values, deleted blank rows, and documented any limitations.  

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

Preventive maintenance should be enhanced, focusing on mechanical failures and "Won't Start" issues. Rigorous pre-trip inspections should be implemented with mandatory checklists, and proactive mid-week maintenance should be scheduled to reduce end-of-week breakdowns. Diagnostic systems should be installed to provide early warnings, and high-breakdown vehicles should be prioritized for proactive maintenance or replacement. These measures are expected to reduce preventable breakdowns by 20–30%.

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

Bus schedules should be adjusted with realistic buffer times for high-traffic routes. Coordination with city traffic management for priority routing during peak hours is essential. Monday-specific operational strategies should be applied to handle traffic surges at the start of the week. These measures are likely to reduce delays by 15–20% and improve overall on-time performance.

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

Company performance disparities should be addressed through audits and tailored improvement plans for underperforming operators. Best practices from top-performing companies should be shared system-wide. Performance metrics should be linked to incentives and contract compliance to improve consistency, reduce delay variability by 15–25%, and ensure accountability.

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

Resources should be reallocated geographically to high-incident boroughs, including additional backup buses and maintenance teams. Satellite maintenance locations and rapid response units should be positioned strategically to reduce disruption duration. Longer schedule buffers should be applied for congested routes. These actions are expected to reduce service disruption duration by 20–30%.

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

Address the Monday delay spike through enhanced Monday-specific operations and resource allocation. Increase Monday staffing levels across all functions including drivers, maintenance personnel, and dispatch coordinators to handle the elevated demand and incident frequency. Position additional backup vehicles specifically for Monday deployment, ensuring rapid replacement capability when delays or breakdowns occur. Build Friday's demonstrated lower delay patterns into capacity planning by potentially redistributing some resources to Monday operations when demand and incident rates are highest, optimizing overall system efficiency across the week.

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

Enhanced weekend maintenance quality control should be implemented, with supervisor sign-offs on all weekend work. Vehicles should be thoroughly checked on Monday mornings before entering service. Proactive mid-week maintenance can catch issues before end-of-week breakdowns. Additionally, Monday-specific resource allocation and traffic coordination should be implemented to handle the start-of-week surge. These measures are expected to mitigate Monday spikes and improve reliability throughout the week.

---

## Summary of Key Findings

1. **Mechanical Issues Dominate Breakdowns**: Mechanical problems and "Won't Start" issues are the leading causes of breakdowns, indicating systematic maintenance gaps that are preventable through enhanced protocols.

2. **Traffic is the Main Delay Driver**: Heavy traffic overwhelmingly causes delays, requiring schedule optimization and coordination with city traffic management rather than just vehicle improvements.

3. **Significant Company Performance Variation**: The top 10 delay-prone companies show substantial performance disparities, presenting opportunities for best practice sharing and targeted interventions.

4. **Geography Matters**: High-density boroughs (Manhattan, Brooklyn, Queens) experience longer delays due to population concentration and traffic congestion, requiring location-specific resource allocation.

5. **Monday Effect is Real**: Both delays and breakdowns spike on Mondays and decline through the week, suggesting weekend maintenance effects and beginning-of-week traffic patterns require operational adjustments.

---

