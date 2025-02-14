
# B&J Biscuit Business Analysis Dashboard


![Dashboard1](/images/20250214144701.png)

## Project Overview
An interactive Excel dashboard created to provide comprehensive business insights for B&J Biscuit, focusing on revenue distribution, profitability analysis, and customer demographics. The dashboard enables data-driven decision-making through dynamic visualizations and flexible filtering options.


## Purpose of project
To demonstrate the methodology behind the creation of the dashboard and the application of Excel formulas, the project began with the analysis of the provided [requirements](/B&J%20Buscuit%20Dashboard%20Requirements.pdf) and [dataset](/B&J%20Buscuit%20Practice%20Dataset.xlsx). The final dashboard can be viewed [here](/B&J%20Buscuit%20Portfolio%20Project.xlsm) or accessed [online](https://thurse1-my.sharepoint.com/:x:/g/personal/137890_office365works_net/ERE2_yM2gs9CpR-DlhgBe2sBfz6ZVljIF6-vyBq-OwcjQQ?e=apADMs).

## 📚 Table of Contents
- [Features](#features)
    - [📊 Revenue Analysis](#-revenue-analysis)
    - [📈 Performance Tracking](#-performance-tracking)
    - [👥 Customer Insights](#-customer-insights)
    - [🎯 Profitability Analysis](#-profitability-analysis)
- [Technical Implementation](#technical-implementation)
    - [📱 Interactive Features](#-interactive-features)
    - [🛠 Technical Solutions](#-technical-solutions)
- [Development Process](#development-process)
    - [Challenges Overcome](#challenges-overcome)
    - [Best Practices Applied](#best-practices-applied)
- [Tools & Resources Used](#tools--resources-used)
- [Future Enhancements](#future-enhancements)

## Features

### 📊 Revenue Analysis
- **Multi-dimensional Revenue Distribution**
  - Demographic breakdown by age group and gender
  - Payment method distribution
  - Geographic revenue share visualization

- **Dynamic Revenue Views**
  - Toggle between absolute values and percentage contributions
  - Interactive charts with highlighting capabilities
  - Custom number formatting (K, M, B) for better readability

### 📈 Performance Tracking
- **Temporal Analysis**
  - Quarter-over-Quarter (QoQ) changes
  - Month-over-Month (MoM) trends
  - Week performance
  - Weekday vs. Weekend comparison

- **Key Performance Indicators**
  - Quantity Sold
  - Total Revenue
  - Cost of Goods Sold (COGS)
  - Total Profit
  - Profit Margin

### 👥 Customer Insights
- Top 5 revenue-contributing customers
- Customer acquisition metrics
- Age group distribution analysis
- Geographic performance breakdown

### 🎯 Profitability Analysis
- Most profitable:
  - Brand
  - Location
  - Customer segment
  - Sales representative

## Technical Implementation

### 📱 Interactive Features
- **Dynamic Filtering**
    - Multiple filter selection capability
- **Toggle Functionality**
    - Switch between percentage and absolute values
    - Interactive chart highlighting
    - Customizable data labels
  

### 🛠 Technical Solutions
- **PivotTable Optimizations**
    - Disabled "Generate GetPivotData" for improved dashboard references
    - Custom PivotTable layout configuration

- **Advanced Excel Formulas**
    - Age calculation: `DATEDIF` implementation
    - Age group categorization: `FLOOR` function
    - Dynamic number formatting using `SWITCH` and `TEXT`
    - Name linked together with `TEXTJOIN`
    - `VLOOOKUP` for creating interactive chart highlighting 


## Development Process

### Challenges Overcome
- PivotTable reference errors resolution
- Implementation of interactive chart highlighting
- Dynamic label formatting for different value ranges
- Multiple button group management

### Best Practices Applied
- Consistent formatting across worksheets
- Efficient formula usage
- Organized data structure
- User-friendly interface design

## Tools & Resources Used
- **Primary Tool**: Microsoft Excel
- **Color Palette**: Adobe Color
- **Icons**: Flaticon

## Future Enhancements
- Resolution adaptation for different screen sizes
