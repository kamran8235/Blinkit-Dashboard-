# Blinkit-Dashboard-
Blinkit Sales & Outlet Insights Dashboard

Interactive Power BI dashboard analyzing Blinkit's retail performance across outlet types, size formats, city tiers, and product categories — built to demonstrate practical business analytics and stakeholder reporting skills.

Overview

This dashboard consolidates Blinkit's sales performance, item distribution, outlet growth trends, and customer ratings into a single, filterable view. It helps retail managers, category leads, and analysts quickly identify which outlet formats, locations, and product categories are driving performance — and where attention is needed.

Business Problem

Blinkit needed a centralized way to monitor performance across a large, varied outlet network. Without a consolidated view, decision-makers lacked fast, comparable answers to questions like: which outlet formats and city tiers are outperforming, which product categories drive the most revenue, and whether customer satisfaction is holding steady as the network scales.

Goal

Build an executive-ready Power BI dashboard that surfaces sales, ratings, and growth trends by outlet type, size, and location — enabling faster, more confident strategic and operational decisions.

Tech Stack

Power BI Desktop — report design and interactive visuals Power Query — data cleaning and transformation DAX — calculated measures (Total Sales, Avg Sales, Avg Rating, etc.) Data Modeling — relationships across sales, outlet, and item tables File formats — .pbix (full report, data embedded) and .png (visual documentation)

Data Source

Simulated retail dataset resembling Blinkit's operational metrics — includes transactional sales, item-level detail, outlet classification (type, size, location tier), outlet establishment history, and customer ratings.

Dashboard Preview

<img width="908" height="503" alt="image" src="https://github.com/user-attachments/assets/6dae5137-9816-422a-b013-5ee1498fceca" />


Blinkit Project Screenshot
Key Features

Top-line KPIs: Total Sales (₹1.20M), Avg Sales (₹141), Items Tracked (8,523), Avg Rating (3.9) Fat Content Analysis: Sales split between Low Fat (₹425.36K) and Regular (₹776.32K) items Item Type Breakdown: Ranked category contribution — Fruits & Veg and Snacks lead, each near ₹0.18M Outlet Establishment Trend (2012–2022): Growth trajectory peaking in 2018 at ₹205K, followed by a plateau Outlet Location (City Tier): Tier 3 leads with ₹472.13K, ahead of Tier 2 (₹393.15K) and Tier 1 (₹336.40K) Outlet Size: Sales are spread across Small, Medium, and High-format outlets, with one format contributing over ₹500K — a healthy spread rather than concentration in a single format Outlet Type Performance: Supermarket Type1 leads by a wide margin at ₹787.55K across 5,577 items — well ahead of Grocery Store, Supermarket Type2, and Type3, each in the ₹130–152K range Interactive Filters: Outlet Location Type, Outlet Size, and Item Type, for granular drill-down

Key Insights & Business Impact

Outlet format concentration: Supermarket Type1 drives the large majority of total sales among outlet types, despite Grocery Store showing a comparable rating and visibility profile — suggesting format, not just footfall, is a major performance lever. Geographic opportunity: Tier 3 cities outperform Tier 1 and Tier 2 in total sales, pointing to strong demand in smaller cities that may be underweighted in current expansion planning. Product mix: Regular fat-content items and high-volume categories (Fruits & Veg, Snacks) are the primary sales drivers, together contributing a majority of category-level revenue. Customer satisfaction is stable, not differentiating: Average ratings sit in a narrow band (roughly 3.91–3.93) across every outlet type. Satisfaction is consistently solid, but it isn't what separates high performers from low performers — the sales gap between outlet types is being driven by format and location, not service quality. Growth trend: Outlet establishment activity was strongest between 2016–2018, peaking in 2018 (₹205K); growth since has been steady but plateaued, suggesting the network may be approaching saturation under its current footprint strategy.

Recommendations

Prioritize Supermarket Type1 in future outlet expansion, given its outsized revenue contribution relative to other formats at similar rating levels. Increase investment in Tier 3 city outlets, where demand is proving strong relative to Tier 1/2 — a potentially underexploited growth segment. Treat rating scores as a baseline, not a differentiator, in outlet performance reviews — since satisfaction is uniformly high, performance conversations should focus on format and category mix rather than service-quality gaps. Re-evaluate the plateaued growth phase (2019–2022) to determine whether it reflects market saturation or reduced expansion investment, before setting next-cycle outlet targets.

Repository Structure

Blinkit-Dashboard/
│
├── BLINKIT.pbix
├── README.md
├── Dashboard.png
├── data/
    └── BlinkIT Grocery Data.xlsx


How to View

Open Blinkit-Dashboard.pbix in Power BI Desktop (free) — the dataset is embedded, so it opens fully populated with no external data connection required.

Author

Saiyed Kamran Alam
