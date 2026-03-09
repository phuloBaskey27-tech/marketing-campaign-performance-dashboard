# Marketing Campaign Performance Dashboard

A Power BI-based analytics dashboard for tracking, analyzing, and optimizing marketing campaign performance across multiple channels and customer segments.

## Overview

This project provides a comprehensive business intelligence solution for monitoring marketing campaign metrics, ROI analysis, and performance trends across different marketing channels. The dashboard aggregates campaign data and generates actionable insights through interactive visualizations and statistical analysis.

## Features

- **Campaign Performance Metrics**: Track campaign reach, engagement rates, conversion rates, and ROI
- **Multi-Channel Analysis**: Compare performance across email, social media, display, and paid search campaigns
- **Customer Segmentation**: Analyze campaign effectiveness by customer demographics and behavior
- **Budget Allocation**: Monitor spend efficiency and cost-per-acquisition across campaigns
- **Trend Analysis**: Visualize performance trends over time with interactive time-series charts
- **Interactive Dashboards**: Drill-down capabilities for detailed campaign-level insights

## Project Structure

### Files

- `campaign_analysis.pbix` - Main Power BI dashboard file
- `campaign_data.csv` - Campaign performance dataset
- `channel_performance.csv` - Channel-specific metrics and KPIs
- `README.md` - Project documentation

## Data Description

The campaign datasets contain the following key metrics:

| Column | Description |
|--------|-------------|
| Campaign_ID | Unique campaign identifier |
| Campaign_Name | Name of the marketing campaign |
| Channel | Marketing channel (Email, Social Media, Display, Paid Search) |
| Start_Date | Campaign launch date |
| End_Date | Campaign end date |
| Budget | Total campaign budget allocated |
| Impressions | Number of ad impressions |
| Clicks | Number of clicks received |
| Conversions | Number of conversions/purchases |
| Revenue | Total revenue generated |
| Cost_Per_Acquisition | Cost per customer acquired |
| ROI | Return on investment percentage |
| Customer_Segment | Target audience segment |

## Requirements

- Power BI Desktop (Latest version)
- Microsoft Excel or CSV viewer
- Power BI Service subscription (optional, for cloud sharing)

## Installation

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Clone or download this repository
3. Open `campaign_analysis.pbix` in Power BI Desktop
4. Refresh data connections to update with latest campaign metrics

## Usage

1. **Open the Dashboard**: Launch the `.pbix` file in Power BI Desktop
2. **Navigate Visualizations**: Use the interactive tabs to explore different campaign metrics
3. **Apply Filters**: Use slicers to filter by date range, channel, or customer segment
4. **Drill Down**: Click on chart elements to explore detailed campaign performance
5. **Export Reports**: Use Power BI's export features to share insights with stakeholders

## Key Dashboards

### Campaign Overview
- High-level KPIs: Total spend, total revenue, overall ROI
- Campaign performance comparison across all channels
- Top performing campaigns by revenue and conversion rate

### Channel Performance
- Channel-wise budget allocation and spend
- Channel-specific conversion rates and engagement metrics
- Cost efficiency comparison across channels

### Customer Segment Analysis
- Campaign performance by customer segment
- Segment-specific ROI and conversion metrics
- Customer acquisition trends by segment

### Budget & ROI Analysis
- Budget utilization across campaigns
- ROI trends over time
- Cost per acquisition by channel and segment

## Key Metrics

- **Impression** - Number of times ad was displayed
- **Click-Through Rate (CTR)** - (Clicks / Impressions) × 100
- **Conversion Rate** - (Conversions / Clicks) × 100
- **Cost Per Click (CPC)** - Budget / Clicks
- **Cost Per Acquisition (CPA)** - Budget / Conversions
- **Return on Investment (ROI)** - (Revenue - Budget) / Budget × 100

## Data Refresh

To update the dashboard with new campaign data:

1. Replace the source CSV files with updated data
2. In Power BI Desktop, go to Home → Refresh
3. Publish to Power BI Service (if using cloud hosting)

## Author

phuloBaskey27-tech

## License

Open source

## Support & Contributions

For questions, issues, or feature requests, please open an issue in the repository.
