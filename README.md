# stock_data_analysis

Here's a step-by-step summary of what this Stock Performance Analyzer notebook accomplishes:

Data Collection & Setup


Automatically tracks stocks across 5 major sectors (Technology, Healthcare, Financial Services, Consumer, Media & Communications)
Fetches real-time stock data using yfinance API
Supports multiple time periods (1, 2, and 3 years)


Interactive Dashboard Features


Sector selection dropdown menu
Performance threshold input (e.g., 20%, 40%)
Time period tabs (1/2/3 years)
Real-time visualizations of stock performance
Generate PDF report button


Performance Analysis


Calculates year-over-year growth percentages
Identifies top and bottom performers
Groups performance by sectors
Tracks initial and final prices
Computes sector-wide statistics


Visualizations


Heat maps showing sector-wise performance
Bar charts for top performers in each sector
Color-coded performance indicators
Interactive plots with hover information


PDF Report Generation


Executive summary with key statistics
Performance threshold-based analysis
Top and bottom performers tables
Sector-wise detailed analysis
Visual representation through charts and heatmaps
Comprehensive tables with growth metrics


Data Organization


Hierarchical structure (Sector → Time Period → Individual Stocks)
Sortable performance metrics
Company details including ticker symbols
Price history and growth calculations


Error Handling & Feedback


API connection management
Data validation
Loading indicators
Success/failure notifications
Graceful fallbacks for missing data

The notebook provides a complete solution for analyzing stock market performance with both interactive exploration capabilities and detailed report generation functionality.
