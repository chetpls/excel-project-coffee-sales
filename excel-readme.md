# Coffee Sales Dashboard Excel Project

## Project Overview
A comprehensive Excel dashboard for analyzing coffee sales data, demonstrating proficiency in data management, Excel functions, and visualization techniques.

## Features
- Advanced Excel formulas (XLOOKUP, INDEX MATCH)
- Data validation and cleaning
- Dynamic dashboards
- Interactive filters and timelines
- Automated reporting

## Technical Skills Demonstrated
### Data Management
- XLOOKUP for customer data retrieval
- INDEX MATCH for product information
- Nested IF statements for data categorization
- Duplicate removal
- Data standardization

### Excel Functions Used
```excel
- XLOOKUP: =XLOOKUP(C2,customers!$A$1:$A$1001,customers!$B$1:$B$1001,,0)
- Nested IF: =IF(I2="Rob","Robusta",IF(I2="Exc","Excelsa",IF(I2="Ara","Arabica",IF(I2="Lib","Liberica",""))))
- INDEX MATCH: =INDEX(products!$A$1:$G$49,MATCH(orders!$D2,products!$A$1:$A$49,0),MATCH(orders!I$1,products!$A$1:$G$1,0))
```

### Data Visualization
- Sales trend line chart
- Country-wise sales bar chart
- Top 5 customers analysis
- Interactive timeline filters
- Dynamic slicers for:
  - Roast type
  - Loyalty card
  - Size

## Project Structure
1. **Raw Data Management**
   - Customer data table
   - Product data table
   - Orders table

2. **Data Processing**
   - Customer lookup implementation
   - Product information retrieval
   - Sales calculations
   - Data cleaning and standardization

3. **Dashboard Components**
   - Total sales visualization
   - Geographic analysis
   - Customer performance tracking
   - Time-based filtering

## Implementation Steps
1. Data Collection and Organization
   - Implemented XLOOKUP for customer information
   - Created product lookup system using INDEX MATCH
   - Established sales calculation formulas

2. Data Cleaning
   - Removed duplicate entries
   - Standardized date formats (MMM-DD-YYYY)
   - Created consistent naming conventions using IF statements

3. Dashboard Creation
   - Built PivotTables for sales analysis
   - Created interactive timeline controls
   - Implemented dynamic slicers
   - Designed visualization charts

## Screenshots
[Include your screenshots here with descriptions]

## Setup Instructions
1. Download the Excel file
2. Enable macros if prompted
3. Ensure all data connections are updated
4. Click 'Refresh All' to update dashboard data

## Future Enhancements
- Additional trend analysis
- Inventory tracking integration
- Automated reporting schedules
- Cost analysis features

## Tools Used
- Microsoft Excel
- PivotTables and PivotCharts
- Excel Tables
- Advanced Excel Functions

## Author
[Your Name]
- GitHub: [Your GitHub Profile]
- LinkedIn: [Your LinkedIn Profile]
