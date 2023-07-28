# Overview
**The screenshots show the BigQuery sample results with the "Why" behind the respective query & offer actionable insights. The data comes from the Google Merchandise GA4 obfuscated sample ecommerce dataset (time period 01/11/2020-31/01/2021).**
---

The screenshot shows the top 10 [product categories by revenue](https://github.com/g-aurig/bigquery_samples/blob/main/productCategoriesByRevenue). 

![Screenshot 2023-07-25 at 10 06 24](https://github.com/g-aurig/bigquery_samples/assets/138019708/0a26d9aa-f8de-41ff-9bdc-1b69a6cb5ac1)

There are at least 3 reasons to look at product categories by revenue: 
1. Revenue generation: focus on & prioritize the most profitable product categories,
2. Ressource allocation: invest in product development & marketing for the high-revenue categories to further boost sales,
3. Strategic decision making: identify growth opportunities & potential expension areas. 

- A safe sign to prioritize the product category 'Apparel' is how the category dominates with a 6.5 times higher revenue compared to the second highest product category 'New'. 
- What about the product category 'Bags' in row 3? What initiatives could be taken to boost sales within this product category? Talk to your trusted product development & marketing team.
---

The screenshot shows the [engagement rate by source/medium](https://github.com/g-aurig/bigquery_samples/blob/main/engagementRateBySource_Medium).

![Screenshot 2023-07-25 at 10 36 28](https://github.com/g-aurig/bigquery_samples/assets/138019708/e45f472b-945c-49eb-8cb2-cd2d8a722863)

Let's consider 2 reasons to investigate the engagement rate by source/medium:
1. Identify top performing channels: focus efforts & resources on the most effective channels, ultimately maximizing ROI,
2. Understand user behaviour: higher engagement rates indicating visitors from these channels are more likely to be interested in the content/product.

- An insight is that the data quality needs a thourough investigation since engagement rates of 1.0 are highly unlikely.
- Another insight is that the spread of the remaining channels is rather small,i.e. 0.61 to 0.73. Despite users coming from quite different channels the overall engagement rate is high. A further in-depth comparison of customer acquisition cost per channel provides further knowledge on how to invest available resources most efficiently. 
---

The screenshot shows the [number of sessions with a purchase per promotion group](https://github.com/g-aurig/bigquery_samples/blob/main/sessionsByPromotionName).

![Screenshot 2023-07-28 at 11 49 24](https://github.com/g-aurig/bigquery_samples/assets/138019708/7b0152c4-1bcb-46d6-963a-67b9b3b26df8)

Below are 3 reasons to be curious about the number of sessions by promotion name where a purchase occurred: 
1. Understanding promotion effectiveness: identifying promotions that drive more sessions & purchases helps in determining which marketing efforts are successful in attracting customers & generating revenue,
2. Optimizing marketing spend: investing more in successful campaigns & reducing spending on less effective ones can lead to better ROI,
3. Seasonal & trend analysis: considering patterns over time enables better planning & preparedness for peak demand periods.

- An initial observation is about data quality. The promotion name shows an empty cell in row 1 & (not set) in row 2. The priority would be to follow up on the tracking, e.g. issues with UTM-parameters.
- The first glimpse shows that the promotion 'Reach New Heights' has driven the largest number of attributable sessions. But what about the CTR or the revenue connected to the promotion?
---




