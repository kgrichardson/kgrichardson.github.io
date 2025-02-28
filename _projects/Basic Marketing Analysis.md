---
layout: page
title: Basic Marketing Analysis
description: Insights from customer segmentation and marketing campaign success analysis
img: assets/img/supermarket.jpg
importance: 1
category: Excel
related_publications: true
---
# Repository Link
Please view my GitHub repository for this project [here](https://github.com/kgrichardson/ABC-Food-Store).

# Summary
This project dives into understanding a small business’s customer base and measuring how well its marketing campaigns are performing&mdash;all using Excel. Customer segmentation helps businesses get a clearer picture of their audience, while comparing campaign results shows whether they’re reaching the right people. These insights shape smarter marketing strategies. With Excel’s built-in **functions**, **PivotTables**, and **visualizations**, analysts can break down the data effectively. A well-designed dashboard brings everything together, giving decision-makers the key takeaways at a glance.

# Scenario
**ABC Food Store**, a local grocery store in a small city&mdash;think Charlottesville, Virginia&mdash;is looking to grow and strengthen its customer base through targeted marketing campaigns. So far, company leaders have launched six campaigns, but they need to know if these efforts are actually working. Now, it's up to the company’s data analyst to assess campaign performance and provide insights that will inform future marketing strategies. By analyzing **customer segmentation**, **purchase patterns**, and **campaign engagement**, the analyst can help optimize marketing efforts for better results.

[//]: # (Adding C-Ville photo)
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/c-ville.jpg" title="Charlottesville" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    If you ever have the change to visit Charlottesville, I highly recommend it! Photo courtesy of the Universtiy of Virginia.
</div>

# Solution
To help company decisionmakers analyze **customer segmentation**, **purchase patterns**, and **campaign engagement** using the provided dataset, a dashboard should include key performance indicators (KPIs) such as total revenue, median (or average) recency, customer segment breakdown, and top-performing campaigns. Additionally, visualizations like a customer segmentation pie chart, a campaign performance chart, and a customer income distribution histogram will help present insights clearly. See the image below for the dashboard layout.

[//]: # (Adding Excel dashboard photo)
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/abc-food-store-dash.png" title="FoodStoreDash" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The dashboard analysis revealed several actionable insights.

First, the **general KPIs** provide valuable context on the company’s performance. While the current analysis offers a snapshot, adding more data over time would enable trend analysis, helping decision-makers track progress and determine whether their actions are delivering the intended results.

Second, the **customer segmentation PivotTable** highlights how different customer groups contribute to the customer base, sales, and campaign engagement. By comparing a segment’s share of total customers to its share of sales, we can identify which groups generate disproportionate revenue. For example, **loyal customers**&mdash;who make up 20% of the customer base&mdash;account for over a third of sales and had a 14% engagement rate in the last campaign. Additionally, the segmentation table shows that the most recent campaign was particularly effective in reaching **dormant** and **at-risk** customers.

Third, the **visualizations** in the dashboard provide further insights. The **customer income histogram** reveals that income levels are evenly distributed around the median household income of `$51,287`. In comparison, the 2020 U.S. median household income was `$67,521`, {% cite censushhldincome2020 %} suggesting that more than half of the company’s customers are likely **budget-conscious** shoppers. The **campaign performance bar chart** displays engagement rates across all campaigns, with an average line for reference. This visualization makes it clear that the most recent campaign had the highest engagement. Lastly, the **customer segmentation pie chart** visually represents the proportion of customers in each segment, with color coding to group similar segments together. Notably, **best** and **loyal** customers—the company’s strongest segments—make up nearly 25% of the total customer base.

Together, these insights help decision-makers refine marketing strategies, optimize customer engagement, and allocate resources more effectively.

## Techniques

### Customer Segmentation
...

### Campaign Success/Engagement
...

### Visualization
...

# Conclusions
This project...

As alluded to above, one problem with the dataset is that there is no time-series data for sales. Therefore, it is hard to tell how sales increase or decline over time. However, assuming Campaign 1 through the last campaign occurred in order, it is possible to compare how customer engagement changed over time.

To continue developing this project, additional data is required to...

# Skills
- Excel
- PivotTables
- ...

# Data Source
Data for this project is from the "ifood-data-business-analyst-test" dataset {% cite nailson2020 %}.