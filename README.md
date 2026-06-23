# 🚲 Bike Sales Dashboard — Excel End-to-End Analysis

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)
![Records](https://img.shields.io/badge/Records-1%2C000-blue)

## Business Scenario

**VeloTrend Bikes** needed to identify which customer segments were most likely to buy, so the marketing team could stop guessing and start targeting. This analysis answers: *who buys, where, and why* — delivered as an interactive Excel dashboard requiring no specialist BI tools.

---

## Project Structure

```
Excel_Project_Dataset.xlsx
├── bike_buyers     ← Raw source data (1,026 rows)
├── Working Sheet   ← Cleaned data + Age Brackets column (1,000 records)
├── Pivot Table     ← Aggregations powering the dashboard
└── Dashboard       ← Interactive charts with slicers
```

**Excel process:** Remove duplicates → standardise labels → derive Age Brackets with nested `IF` → build pivot tables → connect slicers to dashboard charts.

---

## Key Findings

**481 of 1,000 customers (48.1%) purchased a bike.** Here's what separates buyers from non-buyers:

| Factor | Insight |
|---|---|
| **Age** | Middle Age (36–54) converts at **54%** — by far the strongest segment |
| **Commute** | 0–1 mi (**55%**) and 2–5 mi (**59%**) are the sweet spots; 10+ mi drops to 30% |
| **Region** | Pacific **59%** › Europe **49%** › North America **43%** |
| **Marital Status** | Single **54%** vs Married **43%** |
| **Income** | Buyers earn ~$3K more on average ($57,963 vs $54,875) |
| **Occupation** | Professionals convert at **54%**; Management lowest at 42% |

---

## Ideal Buyer Persona

> Single professional, aged 36–54, earning $55K–$80K, commuting under 5 miles — most likely in the Pacific region.

---

## Actionable Recommendations

1. **Target Middle Age singles first** — highest volume *and* conversion rate; this is where ad spend has the clearest ROI
2. **Focus on short commuters (0–5 mi)** — they're the natural bike commuter; lead with utility and cost-saving messaging
3. **Fix North America** — largest market, lowest conversion (43%); run A/B tests on messaging vs Pacific campaigns to diagnose the gap
4. **Don't chase long commuters with standard bikes** — conversion falls off a cliff at 5+ miles; reframe pitch toward e-bikes for this segment
5. **Deprioritise Management segment** — despite higher incomes, they convert least; budget is better spent elsewhere

---

## Excel Skills Used

Data cleaning · Nested `IF` for derived columns · Pivot Tables · Pivot Charts · Slicers · Dashboard layout

---

*[Your Name] | Excel Portfolio Project*
