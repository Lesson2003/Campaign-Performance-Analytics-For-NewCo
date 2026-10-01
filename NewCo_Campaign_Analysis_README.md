# NewCo Campaign Performance Analysis
### Marketing Budget Allocation using Excel Power Query & Power BI

---

## Overview

This project analyzes the performance of a multi-channel marketing campaign for **NewCo**, a big-box retail company, to inform where the business should allocate its next quarter's marketing budget. The analysis was framed as a business case in the style of a BCG X marketing consulting engagement.

NewCo had just completed a campaign that tested a single advertising message in two creative variations (**A** and **B**) across three channels — Email, Instagram, and Web Banner — and needed a data-driven recommendation on where to focus spend going forward.

---

## Business Problem

NewCo ran the same core ad message as two variants (A/B) across three channels:

- 📧 **Email**
- 📱 **Instagram**
- 🌐 **Web Banner**

The business needed to know not just which campaign "won" in aggregate, but which channel-campaign combinations actually drove results — and specifically, what drove engagement and purchases among **new customers**, since new-customer acquisition is a distinct strategic priority from overall revenue.

---

## Brief / Key Questions

1. Which campaign and channel combination performed the best?
2. What generated higher engagement and purchase rates for new customers specifically?
3. Where should the company focus its next quarter's efforts and budget?

---

## Methodology

| Stage | Description |
|---|---|
| **1. Data Import & Shaping** | Campaign and transaction data imported and transformed using **Power Query** (cleaning, structuring, and preparing the dataset for modelling) |
| **2. Dashboard Development** | Interactive dashboard built in **Power BI** to visualize and segment performance across channels, campaigns, and customer types |
| **3. Metric Analysis** | Core and segmented metrics analyzed to identify performance drivers and customer-segment-specific patterns |
| **4. Business Recommendation** | Findings translated into channel/campaign budget allocation recommendations tied to specific business objectives |

### Metrics Tracked on the Dashboard
- Conversion rate
- Average minutes on site
- Total customers
- New customers
- Total revenue
- Revenue by channel
- Revenue by customer
- Revenue by campaign
- New customer sales by channel and campaign

---

## Dataset Summary

- **Total customers:** 500
- **New customers:** 213 (~42.6% of total customer base)
- **Campaign variants tested:** A, B
- **Channels tested:** Email, Instagram, Web Banner
- **Total revenue generated:** ~$14,660 (sum of Campaign A + Campaign B revenue)

---

## Key Findings

### 1. Email drove the highest total revenue
Email accounted for **$7.91K (52.7%)** of total revenue, ahead of Instagram ($3.87K, 25.8%) and Web Banner ($2.88K, 19.2%).

| Channel | Revenue | Share of Total |
|---|---|---|
| Email | $7.91K | 52.7% |
| Instagram | $3.87K | 25.8% |
| Web Banner | $2.88K | 19.2% |

### 2. Campaign B outperformed Campaign A overall
Campaign B generated approximately **$8,790** in total revenue, compared to **$5,870** for Campaign A.

### 3. Email + Campaign B was the top overall combination
Of all channel-campaign pairings, **Email + Campaign B** produced the highest total revenue.

### 4. Campaign A performed better for new customer acquisition
Despite Campaign B's lead in total revenue, the picture flips when isolating **new customers** (213 of the 500-customer base):

| Rank | Channel + Campaign | New Customer Revenue |
|---|---|---|
| 1 | Email + Campaign A | $2,124.47 |
| 2 | Instagram + Campaign A | $969.46 |
| 3 | Web Banner + Campaign A | $633.06 |

Campaign A, despite trailing in total revenue, was the stronger driver of **new customer** sales across every channel.

### 5. The "best" campaign depends on the objective
No single campaign wins across all goals:
- **Campaign B** wins on total revenue
- **Campaign A** wins on new customer acquisition

This means budget allocation decisions must be anchored to a specific business objective rather than a single blended performance metric.

---

## Recommendations

| Objective | Recommended Focus |
|---|---|
| **Maximize total revenue** | Email + Campaign B |
| **Maximize new customer acquisition** | Email + Campaign A |
| **General strategy** | Define the quarter's primary objective *before* allocating budget — "which campaign performed best" is the wrong question; "which channel-campaign combination best serves our objective" is the right one |

**Additional guidance for NewCo:**
- Email is the strongest channel overall and should remain a priority regardless of objective
- If new-customer growth is a strategic priority (e.g. market expansion), Campaign A's creative/messaging approach should be favored over Campaign B
- Budget should not be split evenly across channels/campaigns by default — allocation should be weighted toward the combination that matches the stated quarterly goal

---

## Conclusion

This analysis demonstrates that marketing performance cannot be judged by a single aggregate metric. Segmenting results by channel, campaign, and customer type (new vs. existing) revealed that:

- The campaign with the highest total revenue (B) was **not** the strongest at acquiring new customers
- Channel choice (Email) mattered more consistently than campaign variant for overall revenue
- Effective budget allocation requires the business to define its objective first, then match spend to the channel-campaign combination that best serves that specific goal

Data analysis is only valuable when it's interpreted and translated into an actionable recommendation — this project aimed to do exactly that for NewCo's next-quarter marketing budget decision.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Excel | Source data handling |
| Power Query | Data cleaning, shaping, and transformation |
| Power BI | Dashboard development and data visualization |

---

## Dashboard Metrics Reference

| Metric | Description |
|---|---|
| Conversion rate | Share of visitors/recipients who completed a purchase |
| Average minutes on site | Engagement duration per visitor |
| Total customers | All customers reached across the campaign |
| New customers | Customers acquired for the first time during the campaign (213 of 500) |
| Total revenue | Aggregate revenue across all channels and campaigns |
| Revenue by channel | Revenue breakdown across Email, Instagram, Web Banner |
| Revenue by customer | Revenue breakdown at the individual customer level |
| Revenue by campaign | Revenue breakdown across Campaign A vs. Campaign B |
| New customer sales by channel & campaign | Revenue from new customers only, segmented by channel-campaign combination |

---

## Author

Marketing analytics case study — Excel Power Query & Power BI
