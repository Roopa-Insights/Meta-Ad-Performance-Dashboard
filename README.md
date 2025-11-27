## Overview
Meta Ad Performance Dashboard is a Power BI project that analyzes paid advertising on Facebook and Instagram. It consolidates campaign-level and event-level data to visualize reach, engagement, conversions, and spend, enabling marketers to quickly assess performance and make data-driven decisions.

## Objectives
- Measure performance of paid campaigns across Facebook and Instagram.
- Compare platforms to identify which delivers better reach, engagement, and conversions.
- Optimize budget allocation by identifying high‑ROI campaigns, geographies, and ad formats.
- Improve funnel efficiency by surfacing drop‑off points from impressions → clicks → purchases.
- Inform targeting and timing by revealing top demographics, countries, and hours for engagement.
  
## KPIs
- Impressions: total times ads were shown (count of event_type = Impression).
- Clicks: number of ad clicks (count of event_type = Click).
- Shares: number of times ads were shared (count of event_type = Share).
- Comments: number of user comments (count of event_type = Comment).
- Purchases: conversions attributed to ads (count of event_type = Purchase).
- Engagements: total interactions (Clicks + Shares + Comments).
- CTR: (Clicks ÷ Impressions) × 100.
- Engagement Rate: (Engagements ÷ Impressions) × 100.
- Conversion Rate: (Purchases ÷ Clicks) × 100.
- Purchase Rate: (Purchases ÷ Impressions) × 100.
- Total Budget: sum of campaign spend.
- Avg Budget per Campaign: Total Budget ÷ number of campaigns.
  
## Dashboard (visuals and interactions)
- Donut chart — Gender: dynamic metric split by target gender to identify which gender contributes most to the selected KPI.
- Bar chart — Age groups: engagement and conversions by age cohort to refine audience targeting.
- Map — Country: geographic distribution of the selected metric using color intensity or bubble size.
- Calendar heatmap — Month/Day: monthly and daily activity to detect seasonality and campaign peaks.
- Stacked column — Weekly by Ad Type: weekly trend with stacks for ad formats to compare format contributions over time.
- Area chart — Hourly trend: activity by hour (0–23) to identify optimal delivery windows.
- Matrix — Ad Type × Platform: side‑by‑side comparison of ad formats across Facebook and Instagram.
- Interactions: dynamic measure selector, platform and campaign filters, and drillthrough to campaign-level details.
- <a href="https://github.com/Roopa-Insights/Meta-Ad-Performance-Dashboard/blob/main/Facebook%20Dashboard%20Image.png">Facebook Dashboard Image</a>
- <a href="https://github.com/Roopa-Insights/Meta-Ad-Performance-Dashboard/blob/main/Instagram%20Dashboard%20Image.png">Instagram Dashboard Image</a>
- <a href="https://github.com/Roopa-Insights/Meta-Ad-Performance-Dashboard/blob/main/Meta%20Ad%20performance%20dashboard.pbix"> Dashboard</a>

## Files included
- Project-Files — dataset folder (CSV or source files used to build the dashboard).
- Image Used — folder containing all images and screenshots used in the README and documentation.
- Facebook dashboard — Power BI file or exported assets specific to the Facebook view.
- Instagram dashboard — Power BI file or exported assets specific to the Instagram view.
- Meta-Ad-Performance-Dashboard.pbix — main Power  .
- Documents — Business Requirements Document, Dashboard Insights PDFs and Domain Knowledge Document

## Conclusion
The dashboard demonstrates strong top‑of‑funnel performance (high CTR and engagement) but reveals a conversion gap between clicks and purchases. Prioritize Video and Stories formats, focus on females aged 18–30 in high‑potential countries, schedule delivery in late afternoon/evening, and invest in landing page and retargeting improvements to lift purchase rates and overall ROI.
