# Road Safety Analysis Dashboard

## Project Overview
This Excel-based interactive dashboard analyzes road accident data to identify patterns, hotspots, and contributing factors that impact safety on roads. The dashboard helps users visualize and interpret complex accident data .

## Features
- **Interactive Filtering**: Dynamic data exploration through slicers and dropdown menus
- **Geospatial Analysis**: Map visualization of accident hotspots using latitude/longitude data
- **Temporal Analysis**: Accident trends by time of day, day of week, month, and year
- **Severity Distribution**: Visual breakdown of accident severity with color-coded indicators
- **Contributing Factors Analysis**: Insights into weather conditions, road surface, junction details, and more
- **Dynamic KPI Metrics**: Real-time updates of key performance indicators based on selected filters

## Project Structure
```
Road_Safety_Dashboard.xlsx
├── Data
│   ├── Raw_Data (Original dataset)
│   └── Processed_Data (Cleaned data with calculated columns)
├── Analysis
│   ├── Severity_Analysis
│   ├── Location_Analysis 
│   ├── Time_Analysis
│   └── Factors_Analysis
├── Visualizations
│   └── Accident_Map
├── Dashboard
└── Summary
```

## Implementation Details
The dashboard was developed in Microsoft Excel using the following approach:

### 1. Data Preparation
- Data cleaning and normalization
- Date and time formatting
- Creation of calculated columns for aggregation:
  - Month and Year extraction
  - Time categories (Morning, Afternoon, Evening, Late Night)
  - Day type (Weekday/Weekend)
  - Severity value conversion

### 2. Data Model
- PivotTables for various analysis dimensions
- Summary tables for KPI calculations
- Data relationships and hierarchies

### 3. Visualizations
- Scatter plot with bubble variation for geographical mapping
- Bar and column charts for frequency analysis
- Line charts for temporal trends
- Pie charts for distribution analysis

### 4. Interactive Elements
- Slicers for filtering by:
  - Year and Month
  - Accident Severity
  - Road Type
  - Weather Conditions
  - Day of Week
- Dropdown menus for location and vehicle type filtering
- Dynamic chart updates based on selections

### 5. Insights Section
- Automated identification of high-risk factors
- Conditional insights based on filter selection
- Key recommendations for safety improvements

## How to Use
1. Open the Excel file 
2. Navigate to the "Dashboard" tab
3. Use the slicers and dropdown menus to filter the data
4. Explore the various charts and visualizations
5. Hover over data points for additional details
6. Use the drill-down links to access detailed analysis sheets

## Data Sources
This dashboard uses road accident data with the following key fields:
- Accident_Index
- Accident_Date and Time
- Location (Latitude/Longitude)
- Accident_Severity
- Number_of_Casualties
- Weather_Conditions
- Road_Surface_Conditions
- Junction_Detail
- Light_Conditions
- And more...

## Technical Requirements
- Microsoft Excel (2016 or newer recommended)
- Excel Tables functionality
- PivotTable and PivotChart capabilities
- Scatter chart with bubble variation

## Future Enhancements
- Integration with external data sources for real-time updates
- Advanced statistical analysis of contributing factors
- Predictive modeling for accident risk assessment
- Export functionality for reporting

## Project Status
Completed as Project #3 at Future Intern

## Author
FRIDA KATANA KITSAO 
Future Intern  
https://www.linkedin.com/in/frida-katana-kitsao-701433231/

## Acknowledgments
Special thanks to the Future Intern program for providing the opportunity to work on this meaningful project focused on improving road safety through data analysis.


