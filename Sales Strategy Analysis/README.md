# Project Background
This project was completed as part of the **DataCamp Data Analyst Career Certificate Exam**. Check out the certificate [here](https://www.datacamp.com/certificate/DA0021940315674?trk=public_profile_see-credential). It involves analyzing sales performance data for an office supply company to determine the most effective sales strategy for new product launches. <br><br>


## Project Overview  
**Business Context:** Pens & Printers, founded in 1984, needed to optimize their sales approach for a new product line launch. The company tested three different sales methods over 6 weeks to determine the most effective strategy for future launches.  
**Analysis Period:** 6 weeks post-launch  
**Dataset:** 15,000 customer transactions across multiple US states  
**Revenue Generated:** $1.43 million total  
**Goal:** Identify the most effective sales strategies for future product launches. <br><br>

## Sales Methods Analyzed

1. **Email:** Customers in this group received an email when the product line was launched, and a further email three weeks later. This required very little work for the team.
2. **Call:** Customers in this group were called by a member of the sales team. On average members of the team were on the phone for around thirty minutes per customer.
3. **Email and call:** Customers in this group were first sent the product information email, then called a week later by the sales team to talk about their needs and how this new product may support their work. The email required little work from the team, the call was around ten minutes per customer. <br><br>

## Key Findings

- **Email** was used to target 50% customers and generated $724k in total revenue. It dominates early revenue generation but declines over time (84% → 14% total weekly share).
- **Email+Call** was used to target 17% customers and generated $473k in total revenue. It shows strongest growth trajectory (6x revenue increase by week 6, reaching a 70% share). It also has highest revenue per-sale with median at $185.
- **Call** targeted 33% customers but generated least revenue ($233k) despite high resource investment.
- Performance patterns are consistent across all customer segments and geographic regions. <br><br>

## Analysis Components
### 1. Data Validation & Cleaning
- Standardized 5 inconsistent `sales_method` categories to 3 clean categories.
- Handled 1,074 missing `revenue` values using median corresponding sales method imputation.
- Corrected 2 invalid customer tenure (`years_as_customer`) entries.

### 2. Exploratory Analysis
- Customer acquisition patterns across time, geography, and tenure segments.
- Revenue distribution analysis with transaction clustering at $40-60 and $80-110 ranges.
- Weekly trend analysis showing sales methods' performance evolution.

### 3. Business Metrics
- KPI: Weekly revenue share by sales method (%).
- Secondary Metric: Customer acquisition rate by method. <br><br>

## Recommendations

**Hybrid Strategy Implementation**
- **Weeks 1-2:** Lead with Email-only approach for rapid market penetration.
- **After week 3:** Shift focus to Email+Call for sustained growth and higher transaction values.

**Long-term Considerations**
- Monitor Email+Call performance sustainability beyond week 6.
- Implement weekly dashboard tracking with performance thresholds. <br><br>

## Technical Skills Demonstrated

- **Data Cleaning:** Handled missing values, standardized categories, corrected data inconsistencies.
- **Exploratory Data Analysis:** Multi-dimensional analysis across time, geography, and customer segments.
- **Data Visualization:** Created comprehensive charts and graphs for business insights.
- **Business Metrics:** Defined KPIs and performance monitoring frameworks.
- **Statistical Analysis:** Revenue distribution analysis and trend identification.
- **Business Communication:** Delivered findings through executive report and presentation.

---

*DataCamp Data Analyst Career Certificate Project*  
*Completed: September 2025*
