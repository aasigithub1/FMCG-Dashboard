# AtliQ Mart FMCG Supply Chain Analysis

![Project Banner](fmcg-fast-moving-consumer-goods-acronym-quickly-vector-29140672.jpg)

This repository contains the project files for the supply chain analysis conducted for AtliQ Mart, an FMCG manufacturer in Gujarat, India. The goal of the project was to generate insights and solve service issues to support the company's expansion plans.

## Table of Contents

- [Introduction](#introduction)
- [Situation](#situation)
- [Task](#task)
- [Action](#action)
- [Data Modeling](#data-modeling)
- [Dashboard](#dashboard)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Fast Moving Consumer Goods (FMCG) refer to products that are sold quickly at relatively low cost. These goods are essential items used on a daily basis, such as food, beverages, personal care products, household cleaning products, and over-the-counter medicines.

AtliQ Mart is addressing service issues before expanding to new cities.

![FMCG Products](images/fmcg_products.png)

## Situation

![Situation](business-concept-meaning-situational-analysis-phrase-sheet-219329192.webp)

- • AtliQ Mart, a growing FMCG manufacturer, is headquartered in Gujarat, India, and currently operates in Surat, Ahmedabad, and Vadodara.
- • The company plans to expand to other metros/Tier 1 cities within the next two years.
- • However, AtliQ Mart is facing challenges as some key customers have not renewed their annual contracts due to service issues.
- • Management suspects that late or incomplete deliveries of essential products have led to poor customer service

## Task

![Task](images/task.png)

- **Role**: Peter Pandey, a new data analyst in the supply chain team.
- **Objective**: Track delivery performance metrics daily and create metrics including 'On-time delivery (OT) %,' 'In-full delivery (IF) %,' and 'On-Time In-Full (OTIF) %' against set targets for each customer.
- **Deliverable**: Develop a dashboard based on stakeholder requirements outlined in the business review meeting.

## Action

![Action](images/action.png)

1. **Data Collection**: Gathered data on delivery performance, including timestamps for order placement and delivery.
2. **Metrics Calculation**:
   - **On-time Delivery (OT) %**: Compared actual delivery times with scheduled delivery times.
   - **In-full Delivery (IF) %**: Compared the quantity ordered with the quantity delivered.
   - **On-Time In-Full (OTIF) %**: Combined both metrics to measure orders that are delivered on time and in full.
3. **Dashboard Design**: Used Power BI to design a dashboard that presents these metrics in an easy-to-understand format, with features for monitoring trends, identifying patterns, and flagging deviations from target service levels.

## Data Modeling

![Data Modeling](images/data_modeling.png)

- **Unified View**: Provides a unified view of data from multiple sources, enhancing analysis and decision-making.
- **Efficiency**: Improves efficiency by optimizing query performance, ensuring faster data processing and visualization.
- **Data Integrity**: Ensures data integrity and consistency, fostering trust in the insights derived from Power BI reports.

## Dashboard

![Dashboard](images/dashboard.png)

The dashboard is designed in Power BI and includes the following features:
- Monitoring trends over time
- Identifying patterns in delivery performance
- Flagging deviations from target service levels

[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGY2NDRlYzYtMWU2Yy00NThlLWE5YjMtYzM4ZWJjZWNmMzA5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

## Results

![Results](images/results.png)

- **Key Metrics**: OT%, IF%, OTIF% consistently fall below their targets in recent months.
- **LIFR% and VOFR%**: Remain relatively stable, indicating consistent performance in these areas.
- **Order Volume**: Lotus Mart generates the highest number of orders, while Viveks Stores have the lowest order volume.
- **Undelivered Items**: The highest quantity of undelivered items was observed in May, totaling 78.39k units.
- **Improvement**: Despite efforts, no observable improvement in key metrics recently.
- **Outlier**: AM Milk Product stands out with both the highest order volume and the highest delay time.

## Usage

To use this project, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/atliq-mart-fmcg-analysis.git`
2. Open the project in your preferred IDE.
3. Follow the instructions in the `dashboard` directory to set up Power BI and load the data.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Feel free to reach out if you have any questions or need further assistance. Happy analyzing!
