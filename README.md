# Analyzing-Marketing-Channel-Effectiveness

## :bookmark_tabs: Business Problem

The goal of this analysis was to understand what factors influence conversion rates across different marketing campaigns. Specifically, we wanted to identify which campaign types and marketing efforts (like ad spend, email engagement, and website visits) have the strongest impact on customer conversion.

## :screwdriver: Tools & Technologies Used

| Task                   | Tools                                  | Why? |
|------------------------|---------------------------------------|------|
| Data Source           | Kaggle Dataset                        | Source of raw data |
| Data Extraction       | Pandas                                | Load and filter data |
| Exploratory Data Analysis (EDA) | Python (Matplotlib, Seaborn) | Identify trends and patterns |
| Correlation Analysis  | Scikit-learn                          | Understand relationships between variables |
| Data Visualization    | Matplotlib, Seaborn                  | Generate charts and insights |
| Business Reporting    | GitHub README                        | Document findings and results |


### :mag: Key Insights
#### 1. Conversion Rates Across Campaign Types

The whole campaign variety (including Promotion, Retention, Purchase, and Awareness) showed a relatively equal average conversion rate, which hovers in the range of 10-11%. This proves that there is no single campaign type that would be significantly better than others in terms of making the conversions of the people. However, this is also a potential explanation that we might be focusing and communicating on our targets that are identical across several campaigns, and thus, we have stable performance.

#### 2. Correlation Analysis: What Drives Conversions?

The correlation matrix offered us an overview of which factors exert a significant influence on the level of customer acquisition. Therefore, the most outstanding ones are:

- Ad Spend: A very weak revenue rate from ad spending lead us to the conclusion that simply giving more money does not result in a better conversion rate. That means we must get better at ad targeting and creating ad content than just spending more to win more customers.
- Click-Through Rate (CTR): CTR also showed a weak level of correlation with the rate of conversion so this implies while advertisements may get clicks, they do not promise sales. It may also hint towards a disconnection between the ad and the landing pages of the website.
- Website Engagement (Visits & Time on Site): Besides the fact that there were minimal visits to the site and time spent on the site was also low, it was observed that they did not contribute much to the conversion rate. This hint that while people are spending time on the site, not everyone is clicking through. Improving landing page experience, CTAs, and product offerings could help.
- Email Engagement (Opens & Clicks): Opens and clicks did not show any substantial correlation with the conversion rate, which points to the fact that email marketing attempts might need to be re-examined. Are we targeting the right audience? Is the content striking enough to pull in the desired conversions?

#### 3. Regression Analysis: Do These Factors Actually Predict Conversion?

The data obtained from the regressions supported that none of the tested variables could have a strong, orderly predictive influence on conversion rate. The R-squared value of the model was very low (0.001), which means that almost none of the variance of the dependent variable (conversion rate) is explained by these predictors.

- Ad Spend (p = 0.070): Demonstrated a slightly negative effect in conversion rate although the result did not reach any level of significance.
- Click-Through Rate (p = 0.447): Didn't have any effect on conversion.
- Website Visits (p = 0.284), Email Opens (p = 0.541), and Time on Site (p = 0.459): Neither of these were found to have any visible effect statistically significant.

### :bar_chart: What This Means for Our Marketing Strategy

- Ad spend is not a trigger of conversions. We should allocate resources to target our customers, design ads, and improve the landing page instead of raising the budget.
- Click-through rates do not always mean conversions. The focus should be on improving the post-click user experience (landing page relevance, checkout flow, and user experience) first of all.
- Website interaction is not the only study. People come to the website, but they do not make purchases. We ought to explore the conversion funnel so to see where the customer interest falls away and then fix our strategy accordingly.
