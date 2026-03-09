# Project Overview
This project analyzes a fictional retailer's holiday season performance across online, in-store, and marketplace channels, covering customer segments, campaign types, product categories, shipping operations, and regional outcomes from November 2025 through January 2026.
The goal is to act as an Omnichannel Retail Insights Analyst, surfacing the story behind the numbers, identifying what drove success, and recommending strategies to boost revenue, streamline operations, and elevate the customer experience ahead of the next peak season.
The final deliverable is a two-page interactive Power BI dashboard built for retail managers, category leads, and operations teams incorporating ZoomCharts Drill Down visuals for faster, more intuitive data exploration.


---

# 🎯 Why This Project Matters
The holiday season is the highest-stakes window in retail where three months of performance can define an entire year's profitability. However, most holiday analytics only tells you what sold. This dashboard was built to answer what actually matters:

- 🏪 Which channel is driving profit not just revenue?
- 📦 Where did stockouts and shipping failures silently kill sales?
- 🔁 Are discounts genuinely moving product or just manufacturing returns?

Because in omnichannel retail, the difference between a good holiday season and a great one lives in the details most dashboards never show.

---

## Business Questions
1. Which holiday promotions generated the highest profit margin, and how did performance vary across channels?
2. Did deeper discounts lead to higher return rates, and are certain categories more sensitive?
3. Where did shipping delays peak, and what operational factors contributed most?
4. Which customer segments showed the strongest omnichannel engagement across browsing, purchasing, and returning?
5. Which channel drives the highest profit; not just revenue?
6. Which regions or store locations outperformed expectations, and what explains the difference?
7. Which products stocked out during high-demand windows, and what was the sales impact?
8. How did Pre-Black Friday performance correlate with full-season demand?
9. What percentage of customers engaged across multiple channels and did they generate higher LTV?
10. Which marketing campaigns drove the strongest lift in traffic, conversions, and repeat purchases?

---

## Dataset
- Source: FP20 Analytics Challenge 33 - December 2025
- Business Type: Fictional Omnichannel Retailer
- Period covered: November 2025 – January 2026
- Channels: Web, Store, Marketplace
- Campaign types: Black Friday (BF), Cyber Monday (CM), Holiday, Clearance
- Customer segments: Loyalty-Gold, Loyalty-Silver, Loyalty-Bronze, Returning, New
- Region: NE, West, MW, SE, Canada, SW
- Industries: Healthcare, Financial Services, Technology, Logistics, Retail & E-commerce, Education, Manufacturing.

---

## Tools and Technologies

| **Tool/Technique** | **Usage** |
|---------------|-------------|
| **PowerBI desktop** | Dashboard design, Report publishing |
| **ZoomCharts visual drilldown** | Interactive drill-down on shipping, campaign, and product performance charts |
| **DAX - Data analysis expression** | Profit margin %, repeat purchase rate, omnichannel customer %, LTV calculations, stockout impact |
| **Power Query** |Data cleaning, date table |
| **Data Modelling** | Star schema connecting orders, customers, products, campaigns, and geography |

---

## 💡 Key Insights
- Web drives 60.37% of profit despite being one of three channels. it is not just the largest channel, it is doing the heavy lifting for the entire business.
- Cyber Monday outperforms Black Friday on profit margin. CM generates 26.12% margin vs BF's 25.66%. The assumption that BF is the most profitable holiday event is wrong for this retailer.
- Deeper discounts did not increase return rates. One of retail's most feared trade-offs does not hold for this retail business.
- Footwear stocked out for 12 days during peak demand creating a demand gap that could not be recovered. In high-demand windows, a stockout is not just a missed sale, it is a customer sent to a competitor.
- 44.25% of customers shopped across multiple channels, nearly half the customer base is already omnichannel, yet average basket size and LTV show no significant difference between single-channel and omnichannel shoppers in this period. The omnichannel premium is not yet being captured.
- NE region accumulated the most unshipped orders despite similar delay rates across all regions. This means that NE's problem is volume management, not carrier performance. The same delay rate on a larger order base creates disproportionate fulfilment pressure.

---

## 🔑 Key Takeaways
- Web is the profit engine. Every channel investment decision should be evaluated against its impact on Web performance first.
- CM is underrated and underfunded. If Cyber Monday generates higher margins than Black Friday, it deserves equal or greater campaign investment, not second-billing.
- Discount strategy can be bolder. Data shows discounts do not drive returns. The business has more pricing flexibility than it may currently be exercising.
- Stockout management is a direct revenue leak. 12 days of Footwear stockout during peak season is not an inventory oversight, it is a measurable, preventable revenue loss.
- The omnichannel LTV opportunity is unrealized. 44.25% of customers use multiple channels but are not generating meaningfully higher baskets. There is a cross-channel personalization and incentive gap to close.
- Pre-BF trends are a reliable demand signal. The positive correlation between early-season and full-season performance means retailers can use October/early November data to make smarter inventory and staffing decisions before the peak hits.

---

## ✅ Strategic Recommendations
- Elevate Cyber Monday to equal Black Friday in budget and creative investment. Its margin advantage makes it the more profitable event and if treated as secondary, it means money os eing left on the table.
- Use Pre-BF sales data as a formal demand forecast input. The early-season correlation is strong enough to build a predictive model that improves inventory positioning before peak week.
- Solve Footwear stockout proactively. Build a 12–15 day safety stock buffer for top-selling Footwear SKUs ahead of November. The 12-day outage this season likely cost more than the carrying cost of that buffer.
- Increase NE region's fulfilment capacity before next holiday season. NE's issue is order volume overwhelming carrier capacity, not really delays. Pre-positioning inventory and adding carrier agreements in the NE region will prevent the same accumulation next year.
- Build an omnichannel incentive program to convert the LTV gap. With 44.25% of customers already multichannel, a targeted rewards structure for cross-channel engagement (browse Web, buy in-store; or vice versa) could unlock meaningful AOV and LTV uplift.
- Reallocate Clearance campaign spend toward Holiday and CM. Clearance generates the lowest margin (21.16%) and lowest repeat purchase rate (0.08). Shifting budget to Holiday (22.52% margin, 0.34 repeat rate) generates better outcomes on both dimensions.

---

## Dashboard Visualization  

[**View pbix, pdf snapshot excel and docs file**](https://drive.google.com/drive/folders/16wMfe288hLWujMVQWpogLDoZJrtWNIaA?usp=drive_link)

---

## 🤝 Connect & Feedback
If you found this project useful or have suggestions, feel free to:

- ⭐ Star this repository
- 🐛 Open an issue for feedback or questions
- 🔗 Connect on LinkedIn — [Opeyemi Ayodeji](https://www.linkedin.com/in/opeyemi-ayodeji-86a696b0/)
