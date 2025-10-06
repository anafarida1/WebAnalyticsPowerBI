Web Analytics Dashboard in Power BI with DAX

🎯 Objective:
This project uses Power BI and DAX to analyze website data and track key performance indicators (KPIs) for 2024, providing insights into user behavior, marketing performance, and engagement across devices through an interactive dashboard that measures website activity, conversions, traffic sources, and device usage to support data-driven decisions.

📊A. Core Metrics Overview: Understanding Overall Engagement
The dashboard highlights key website engagement indicators for 2024:

Total Page Views: 8.37M, exceeding the target of 7.68M by 697K (+9%)
Average Bounce Rate: 34.35%
Total Sessions: 500K
Average Session Duration: 1 minute 12 seconds
These metrics provide a quick snapshot of how effectively users are interacting with the site and whether engagement goals are being achieved.

💡 B. Conversion Insights: Evaluating Funnel Effectiveness
Conversion analysis was a core component of this project. Using DAX measures, sessions were categorized as converted or not converted to understand marketing effectiveness.

In 2024, the overall conversion rate was 68%, highlighting strong funnel performance.
This breakdown allows marketing teams to pinpoint which campaigns or landing pages drive the most meaningful interactions.

🌐 C. Traffic Source Analysis: Identifying Top Performing Channels
Traffic sources were analyzed to uncover which acquisition channels contribute most to website activity:

Paid Search: 51%
Organic Search: 30%
Social Media: 10%
Referral: 5%
Direct: 4%
These insights guide budget allocation and optimization across marketing channels.

📱 D. Device Usage: Optimizing for Cross-Platform Experience
To ensure the best possible experience across devices, sessions were analyzed by platform:

Mobile: 4.64M
Desktop: 2.49M
Tablet: 1.24M
With mobile driving the majority of traffic, this insight emphasizes the importance of responsive design and mobile-first strategies.

🌍 E. Target Performance Comparison by Country
Geographic insights highlight how different markets contributed to overall website performance, revealing strong engagement from India and the United States, solid activity in Nigeria and Germany, and growing audiences in Australia, the United Kingdom, and Canada. This regional overview helps identify key markets driving traffic and areas with potential for further growth and optimization.

⚙️ F. Power BI + DAX
Key metrics were calculated using DAX to make the dashboard fully interactive across filters like date, country, traffic source, and device type.
% Converted = DIVIDE(CALCULATE([Total Page Views], 'website analytics dataset'[Conversion Status] = "Yes"), [Total Page Views])
Average Session Duration = AVERAGE('website analytics dataset'[Session Duration (sec)])
Visuals such as stacked bars, pie charts, and slicers make it easy to explore trends by segment or time period.
