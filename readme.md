# Coffee Sales Dashboard Excel Project

## Project Overview
A comprehensive Excel dashboard for analyzing coffee sales data, demonstrating proficiency in data management, Excel functions, and visualization techniques.
[Coffee data from mochen862]([(https://github.com/mochen862/excel-project-coffee-sales])

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
     ![xlookup](/img/1-xlookup.png)
   - Created product lookup system using INDEX MATCH
     ![indexmatch](/img/1-index_match.png)
   - Established sales calculation formulas
     ![sales](/img/1-sales.png)

2. Data Cleaning
   - Removed duplicate entries
     ![duplicate](/img/2-removed_duplicate.png)
   - Standardized date formats (MMM-DD-YYYY), size (kg), price ($)
     ![format](/img/2-format_dates_size_price.png)
   - Created consistent naming conventions using IF statements
     ![namingconvention](/img/2-naming_conventions.png)

3. Dashboard Creation
   - Built PivotTables for sales analysis
     ![pivottable](/img/3-pivot_table.png)
   - Created interactive timeline controls
     ![timeline](/img/3-timeline_2dline.png)
   - Implemented dynamic slicers
     ![slicers](/img/3-slicers.png)
   - Charts for country sales and customer sales
     ![country](/img/3-country.png)
     ![customer](/img/3-customer.png)
   - Designed visualization charts
     ![dashboard](/img/3-dashboard.png)


## Tools Used
- Microsoft Excel
- PivotTables and PivotCharts
- Excel Tables

