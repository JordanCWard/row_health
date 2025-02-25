# <p align="center"> Row Health Campaigns </p>



Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, they introduced a range of marketing campaigns covering wellness tips, plan affordability, and preventative care. Row Health offers four plan tiers—bronze, silver, gold, and platinum—each featuring different premium levels and claim coverage rates.

The primary goal is to evaluate how Row Health’s 2019 marketing campaigns influence signups for these plan tiers and subsequent patient claims. The outcome involves creating a dashboard and regular-cadence reports that enable the marketing team to independently explore insights and measure the effectiveness of their campaigns over time.

The entity relation diagram (ERD) can be found [here](https://github.com/JordanCWard/Row_Health/blob/8e34947d1fc025c04dfe5a50cb3793ac9777c182/ERD.png). <br> <br>

### Executive Summary

Row Health’s primary objectives are to measure how the 2019 marketing campaigns influenced signups for its four plan tiers—bronze, silver, gold, and platinum—and the resulting patient claims. The overarching goal is to create a dashboard and regular reports empowering the marketing team to independently explore campaign effectiveness, allocate budgets more efficiently, and refine messaging strategies for each plan tier and target state.

In 2019, Silver dominated with the highest claims (43,179), the most clicks (794,857), and the lowest cost per signup ($2.42). By contrast, Platinum generated a strong click-through rate (11.27%) yet saw a 0% signup rate, resulting in a very high cost per signup ($490.77). Low-cost, high-performance campaigns such as Campaign 31 ($0.23 per signup) and Health Awareness ($0.92 per signup) underscore the potential of budget reallocation, while high-expense channels like Campaign 5 ($1,519.17 per signup) warrant restructuring. Regionally, New Jersey achieved both high volume (26,279 claims) and a favorable cost per signup ($4.10), whereas Florida registered the fewest claims (14) alongside the most expensive cost per signup ($1,011.84). By focusing on these standout opportunities and addressing bottlenecks in underperforming areas, Row Health can optimize plan enrollments and marketing ROI moving forward.


### High-Impact Recommendations

- **Consolidate Budget Around Low-Cost, High-Performance Campaigns:** Shift more resources toward Campaign 31 (lowest cost per signup at $0.23), Health Awareness (lowest cost per signup at $0.92), and Campaign 14 (CPC $0.00) to capitalize on their high efficiency. Simultaneously, deprioritize or restructure high-cost efforts such as Campaign 5 (cost per signup $1,519.17) and Offer Announcement (cost per signup $69.61).

- **Leverage Silver Plan’s Strong Results:** With the highest number of claims (43,179), highest clicks (794,857), and the lowest cost per signup ($2.42), Silver demonstrates outstanding performance. Expand marketing around Silver’s success stories—like its #HealthyLiving campaign—to boost overall conversions and replicate best practices across other plans.

- **Optimize by State to Balance Cost and Volume:** While NJ dominates in both claims and clicks, it also offers a relatively low cost per signup ($4.10). Further increase investment in NJ to maximize high-volume returns. At the same time, investigate ways to reduce costs in high-expense states like FL ($1,011.84 per signup) or shift focus to DC, which delivers the lowest CPC ($0.03).

- **Refine Platinum’s Signup Funnel:** Despite a strong click-through rate (11.27%) and a low CPC ($0.04), Platinum yields a 0% signup rate, pushing its cost per signup up to $490.77. Conduct a thorough funnel analysis to identify drop-off points, optimize landing pages, and tailor messaging (e.g., Affordable Plans, #CoverageMatters) to convert curious prospects into actual signups.
<br>


### Dashboard

The dashboard was created in Tableau. <br>

<img width="800" alt="Campaign Category Dashboard" src="https://github.com/user-attachments/assets/783cd15d-bb44-4162-9e51-f13a7c6ccf0c" />

[View the dashboard on Tableau Public](https://public.tableau.com/views/row_health_tableau/CampaignCategoryDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) <br> <br>


## <p align="center"> Insights Deep-Dive </p>

This analysis was focused on providing insights in the following key areas:

- [Campaign ID](#campaign-id)
- [Campaign Type](#campaign-type)
- [Plans](#plans)
- [State](#state)  <br> <br>


### Campaign ID
- **Claims**: Campaign 18 recorded the highest (11,590).
- **Clicks**: Campaign 27 had the most (47,785), while Campaign 33 had the fewest (0).
- **Cost per Click**: Campaign 14 offered the lowest ($0.00), and Campaign 5 had the highest ($0.65).
- **Cost per Signup**: Campaign 31 had the lowest ($0.23), whereas Campaign 5 had the highest ($1,519.17). <br> <br>


### Campaign Type
- **Claims**: Product Promotion had the highest (16,897), while Offer Announcement had the lowest (164).
- **Clicks**: Policy Information recorded the highest (256,970), while Health Tips had the lowest (42,940).
- **Cost per Click**: Health Awareness and Policy Information both had the lowest ($0.03), while Customer Testimonial saw the highest ($0.07).
- **Cost per Signup**: Health Awareness achieved the lowest ($0.92), whereas Offer Announcement had the highest ($69.61). <br> <br>


### Plans
- **Claims and Clicks**: Silver led both metrics with 43,179 claims and 794,857 clicks, while Platinum had the fewest (39 claims, 138,153 clicks).
- **Cost Metrics**: Bronze, Silver, and Platinum shared the lowest cost per click (CPC) at $0.04, while Gold’s was slightly higher at $0.05. Silver offered the lowest cost per signup ($2.42), whereas Platinum’s stood at $490.77.
- **Plan Highlights**:
  - **Bronze**: Second highest cost per signup at $23.90, top campaign is *Preventative Care News*.
  - **Silver**: Highest signup rate at 0.17%, top campaign is *#HealthyLiving*.
  - **Gold**: Lowest CTR at 8.80%, top campaign is *#CoverageMatters*.
  - **Platinum**: Highest CTR at 11.27%, highest cost per signup at $490.77. <br> <br>


### State
- **Claims**: NJ recorded the most (26,279), while FL had the fewest (14).
- **Clicks**: NJ registered the highest number of clicks (733,612), whereas FL had the lowest (95,178).
- **Cost per Click**: DC had the lowest ($0.03), and KS posted the highest ($0.07).
- **Cost per Signup**: NJ offered the lowest ($4.10), while FL showed the highest ($1,011.84).
