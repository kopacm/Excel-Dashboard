
# B&J Biscuit Business Analysis Dashboard


![Dashboard1](/images/20250214144701.png)

## Project Overview
An interactive Excel dashboard created to provide comprehensive business insights for B&J Biscuit, focusing on revenue distribution, profitability analysis, and customer demographics. The dashboard enables data-driven decision-making through dynamic visualizations and flexible filtering options.

## Features

<details>
    <summary><h3>📊 Revenue Analysis</h3></summary>

    <ul>
        <li><strong>Multi-dimensional Revenue Distribution</strong>
            <ul>
                <li>Demographic breakdown by age group and gender</li>
                <li>Payment method distribution</li>
                <li>Geographic revenue share visualization</li>
            </ul>
        </li>
        <li><strong>Dynamic Revenue Views</strong>
            <ul>
                <li>Toggle between absolute values and percentage contributions</li>
                <li>Interactive charts with highlighting capabilities</li>
                <li>Custom number formatting (K, M, B) for better readability</li>
            </ul>
        </li>
    </ul>
</details>

<details>
    <summary><h3>📈 Performance Tracking</h3></summary>

    <ul>
        <li><strong>Temporal Analysis</strong>
            <ul>
                <li>Quarter-over-Quarter (QoQ) changes</li>
                <li>Month-over-Month (MoM) trends</li>
                <li>Week performance</li>
                <li>Weekday vs. Weekend comparison</li>
            </ul>
        </li>
        <li><strong>Key Performance Indicators</strong>
            <ul>
                <li>Quantity Sold</li>
                <li>Total Revenue</li>
                <li>Cost of Goods Sold (COGS)</li>
                <li>Total Profit</li>
                <li>Profit Margin</li>
            </ul>
        </li>
    </ul>
</details>

<details>
    <summary><h3>👥 Customer Insights</h3></summary>

    <ul>
        <li>Top 5 revenue-contributing customers</li>
        <li>Customer acquisition metrics</li>
        <li>Age group distribution analysis</li>
        <li>Geographic performance breakdown</li>
    </ul>
</details>

<details>
    <summary><h3>🎯 Profitability Analysis</h3></summary>

    <ul>
        <li>Most profitable:
            <ul>
                <li>Brand</li>
                <li>Location</li>
                <li>Customer segment</li>
                <li>Sales representative</li>
            </ul>
        </li>
    </ul>
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
