
# B&J Biscuit Business Analysis Dashboard


![Dashboard1](/images/20250214144701.png)

## Project Overview
An interactive Excel dashboard created to provide comprehensive business insights for B&J Biscuit, focusing on revenue distribution, profitability analysis, and customer demographics. The dashboard enables data-driven decision-making through dynamic visualizations and flexible filtering options.

## Features

### 📊 Revenue Analysis
<details>
    <summary>**Multi-dimensional Revenue Distribution**</summary>
    
    - Demographic breakdown by age group and gender
    - Payment method distribution
    - Geographic revenue share visualization
</details>

<details>
    <summary>**Dynamic Revenue Views**</summary>
    
    - Toggle between absolute values and percentage contributions
    - Interactive charts with highlighting capabilities
    - Custom number formatting (K, M, B) for better readability
</details>

### 📈 Performance Tracking

<details>
    <summary>**Temporal Analysis**</summary>
    
    - Quarter-over-Quarter (QoQ) changes
    - Month-over-Month (MoM) trends
    - Week performance
    - Weekday vs. Weekend comparison
</details>

<details>
    <summary>**Key Performance Indicators**</summary>
    
    - Quantity Sold
    - Total Revenue
    - Cost of Goods Sold (COGS)
    - Total Profit
    - Profit Margin
</details>

### 👥 Customer Insights

<details>
    <summary>Top 5 revenue-contributing customers</summary>
    
    - Customer acquisition metrics
    - Age group distribution analysis
    - Geographic performance breakdown
</details>

### 🎯 Profitability Analysis

<details>
    <summary>Most profitable:</summary>
    
    - Brand
    - Location
    - Customer segment
    - Sales representative
</details>

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

### 🎨 Design Elements
- Color scheme selected using Adobe Color
- Professional icons from Flaticon
- Responsive layout design
- Clear visual hierarchy

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
