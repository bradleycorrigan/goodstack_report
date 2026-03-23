# GoodStack Report - Complete Analysis Summary

## Executive Overview
- **Total Donations:** 500
- **Total Value (USD):** $35,133.77
- **Average Donation Value:** $70.27
- **Unable to Pay Rate:** 51.80% ⚠️
- **Settled Rate:** 0.00%
- **Total Organisations:** 143
- **Total Partners:** 7
- **Top Payment Method:** bank_transfer (54.2%)

---

## Key Insights & Analyses Added

### INSIGHT #1: Unable to Pay Status Deep Dive (51% of all donations)
**Finding:** Over half of all donations are marked as "unable_to_pay" - a critical issue requiring investigation.

**Breakdown by Partner:**
- Partner_Name_1: Dominates with majority of unable_to_pay cases
- Other partners have scattered instances

**Breakdown by Country:**
- Australia leads in unable_to_pay volume
- United Kingdom also significantly affected
- Top affected countries: Australia, Germany, Romania, Netherlands, United States

**Payment Methods (Unable to Pay):**
- unable_to_pay: 259 records (payment method classification)
- bank_transfer: Used for many unable_to_pay cases
- card, cheque also present

**Recommendation:** Investigate payment processing failures, gateway issues, or compliance blocks (especially common in AU/UK/DE/RO).

---

### INSIGHT #2: Partner_Name_1 Deep Dive
**Finding:** Partner_Name_1 is the dominant partner, processing significantly more donations than any competitor.

**Statistics:**
- **Total Donations:** 290 (58% of all donations)
- **Total Value (USD):** $34,244.02 (97.47% of total)
- **Average Donation Value:** $118.09 (highest among partners)
- **Status Breakdown:**
  - unable_to_pay: 152 donations (52.4%)
  - paid: 105 donations (36.2%)
  - Other: remainder

**Top Countries (Partner_Name_1 Activity):**
1. United Kingdom: $10,918+ (98 donations)
2. Australia: $9,850+ (78 donations)
3. Germany: $4,786+ (41 donations)
4. Romania: $3,046+ (13 donations)
5. Netherlands: $2,156+ (19 donations)

**Top Organisations (Partner_Name_1):**
- Organisation_Name_48 (Germany): Highest value recipient
- Multiple UK-based organisations receiving consistent support
- Strong presence across 10+ major organisations

**Strategic Note:** Partner_Name_1 represents critical business concentration risk (97.47% of volume).

---

### INSIGHT #3: Organisations Per Region Over Time (Onboarding Trends)
**Finding:** Organisations are onboarding over time in specific geographies, indicating growing network expansion.

**Top 5 Countries by Organisations Onboarded:**
1. United Kingdom: Largest onboarding volume
2. Australia: Second largest
3. Germany, Romania, Netherlands: Growing presence

**Timeline:**
- Consistent monthly onboarding activity
- Recent months show continued growth in multiple regions
- UK and AU onboarding particularly strong in recent periods

**Visualization:** Stacked area chart shows regional onboarding trends over time.

---

### INSIGHT #4: Organisations Operating Across Multiple Countries
**Finding:** Currently 0 organisations operate across multiple countries in the dataset.

- **Total Organisations:** 143
- **Multi-Country Organisations:** 0 (0%)
- **All organisations operate in single countries only**

**Strategic Implication:** Network expansion is geography-focused rather than cross-border operations. Opportunity for expansion strategies targeting multi-country organisations.

---

### INSIGHT #5: Donations by Foundation/Organisation

**Top 10 Foundations by Donation Value:**
- Foundation_Name_2: Highest contributor
- Foundation_Name_1: Secondary contributor
- Most foundations have single-digit donation counts

**Top 15 Organisations by Donation Value:**
1. Organisation_Name_48 (Germany): Highest value recipient
2. Organisation_Name_77 (Australia): Strong performer
3. Multi-country mix with UK and AU organisations dominating

**Organisation Statistics:**
- **Total Unique Organisations:** 143
- **Average Donations per Org:** 3.5
- **Median Donations per Org:** 2
- **Top Organisation:** 26 donations

---

### INSIGHT #6: Average Donation Value Trends Over Time
**Finding:** Average donation values fluctuate monthly with overall trend around $70.27.

**Metrics:**
- **Overall Average:** $70.27
- **Median:** $30.00
- **Range:** $0.01 (minimum) to $1,000.00+ (maximum)

**Monthly Trends:** 
- Visualized in chart 6 showing variation across months
- Overall line relatively stable with volatility
- Green reference line shows overall average baseline

---

## Visualizations Generated

1. **1_donations_over_time.png** - Monthly total donation trends (original)
2. **2_top_countries.png** - Top 10 countries by contribution (original)
3. **3_status_breakdown.png** - Donation status pie chart (original)
4. **4_top_partners.png** - Top 5 partners by volume (original)
5. **5_cumulative_donations.png** - Cumulative donation curve showing growth
6. **6_avg_donation_over_time.png** - Average donation value trends with baseline
7. **7_unable_to_pay_by_country.png** - Unable to pay status by country breakdown
8. **8_org_onboarding_by_country.png** - Organisation onboarding trends over time
9. **9_top_orgs_by_volume.png** - Top 10 organisations by donation count
10. **10_payment_method_vs_status.png** - Status distribution by payment method

---

## Tables Generated

All analyses include readable data tables for deeper examination:
- Monthly trends with cumulative totals
- Country rankings with percentages
- Partner performance metrics
- Status breakdowns
- Foundation and organisation statistics
- Unable to pay analysis by country, partner, payment method
- Partner_Name_1 competitive analysis

---

## Critical Business Issues to Address

1. **51.8% Unable to Pay Rate** - Largest issue requiring immediate investigation
   - Check payment processing failures
   - Review compliance/KYC issues
   - Audit gateway integrations
   
2. **Business Concentration Risk** - 97.47% of volume from Partner_Name_1
   - Develop partner diversification strategy
   - Reduce dependency on single partner
   
3. **Zero Multi-Country Operations** - Missing cross-border growth opportunity
   - Consider products/services targeting multi-country operations
   - Expand beyond single-geography organisations

4. **Geographic Concentration** - 59.11% of value in UK+AU
   - Develop market entry strategies for underrepresented regions
   - Consider localization needs

---

## Data Quality Notes

- 500 total donation records analysed
- 143 unique organisations across 35+ countries
- 7 partner organisations
- 2 foundation entities
- Data spans multiple transaction statuses and payment methods
