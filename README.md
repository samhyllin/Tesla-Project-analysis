# Tesla-Project-analysis
## Background

Tesla’s growth over the past decade has drawn massive public attention, both in the market and online. This project examines how web search interest relates to Tesla’s stock performance. Using Google Trends data and historical stock prices, I track yearly search volumes and compare them to stock price movements. The analysis highlights patterns where public interest rises alongside major price changes, giving a clear view of the relationship between attention and market value.
```
📁 Project Structure
│
├── 📁 data
│ └── 📄 TESLA Search Trend vs Price.csv
│
├── 📁 notebooks
│ └── 📄 tesla_analysis.ipynb
│
├── 📁 images
│ ├── 📄 yearly_search_bar_chart.png
│ └── 📄 tesla_search_vs_price.png
│
└── 📄 README.md
```

## Data Cleaning
Key steps in preparing the dataset included:
```
• Checking for and dropping any missing values
• Converting the MONTH column from text to datetime format for accurate time-based analysis
• Extracting the year from the MONTH column for yearly aggregation
• Ensuring numeric columns like TSLA_WEB_SEARCH and TSLA_USD_CLOSE are correctly typed
```
These steps ensured the dataset was complete, structured, and ready for meaningful analysis.

## Analysis and Visualization
The analysis focused on several key areas:
```
• Yearly Tesla Search Volume
• Aggregated monthly search trends into yearly totals
• Visualized with a bar chart to show changes in public interest over time

• Tesla Stock Price vs Web Search Trends
• Plotted stock price and search trends on a dual-axis line chart
• Highlighted how spikes in search activity often correspond with notable stock movements

• Descriptive Statistics
• Calculated max, min, mean, and standard deviation for stock price and search trends
• Provided insight into the scale and variability of both metrics
```

## Project Overview
This project analyzes Tesla Google search trends and Tesla stock closing price over time.
```
- Loaded real Tesla search trend and stock price data
- Cleaned the dataset and fixed date formats
- Checked missing values and data types
- Summarized yearly search trends
- Visualized trends with bar charts
- Plotted search interest and stock price on one chart
- Compared attention spikes with price movement
```

## Tools Used
```
• Python
• pandas for data cleaning and aggregation
• matplotlib for static visualizations
• plotly for interactive visualizations
```

 ### What this project shows
 ```
- Public interest in Tesla increased over the years
- Big spikes in search activity often match strong price movement
- Attention and market value move together in many periods
```

## Key Insights
```
• Tesla web searches have grown steadily over the last decade, with notable spikes in specific years indicating periods of high public interest
• Peaks in search activity often coincide with significant stock price movements, suggesting a link between public attention and market value
• Tesla’s stock price shows high variability over the years, while search trends demonstrate a more gradual upward pattern
• Yearly aggregation of search trends makes it easy to identify the most active years for Tesla’s public attention
```

## Executive Summary

This project explores the link between public interest in Tesla and its stock performance over the past decade. Using Google Trends data and historical stock prices, I aggregated monthly search activity into yearly totals and compared it with Tesla’s stock price. The analysis reveals clear patterns where spikes in search interest align with major price movements, showing how public attention corresponds with market value. Visualizations include interactive yearly search volume charts and dual-axis plots of search trends versus stock price, providing a clear, data-driven view of Tesla’s popularity and market behavior.
