# Marketing A/B Testing

Purpose of this project is about analyzing the effect of online advertisements on the sales of a large company with a substantial user base. The company conducted an A/B test for 31 days, exposing 20000 customers to either ads (the experimental group) or public service announcements (PSA) (the control group). The goal is to answer two questions:

- Would the campaign be successful?
- If the campaign was successful, how much of that success could be attributed to the ads?

## Data Description

The data set contains information about each customer who participated in the A/B test, such as:

- **customerID:** unique identifier for the customer.
- **test group:** consists of AD (the experimental group) and PSA (control group).
- **made_purchase:** a Boolean value representing whether or not the user made a purchase after seeing an advertisement.
- **days_with_most_ad:** A day of the month when the user saw the most ads
- **peak ad hours:** an hour of the day when the user saw the most ads.
- **ad_count:** total number of ads seen by each user.

## Analysis

The analysis is performed using Python and Jupyter Notebook. The main steps are:

- Data exploration
- Hypothesis testing using Chi-squared test
- Visualization of results using seaborn

The analysis and data can be found in this repository.

## Results

The main findings of the analysis are:

- The campaign was successful, as the proportion of customers who made a purchase after seeing an ad was significantly higher than the proportion of customers who made a purchase after seeing a PSA (p-value < 0.05).
- The ads had a positive impact on sales, as the average revenue per customer in the experimental group was higher than the average revenue per customer in the control group.
- The optimal number of ads per month is 5 or 7, as these values had the highest conversion rates among all ad counts.
- The experimental group had a higher conversion rate on days 19-23 of the month, which could be due to seasonal factors or other external influences.
- The experimental group had a higher conversion rate early in the morning (1 am - 5 am), which could be due to lower competition or higher attention span at that time.

## Conclusion

The analysis suggests that online advertisements can increase sales for the company, and that there are some factors that can influence the effectiveness of the ads, such as the number of ads, the day of the month, and the hour of the day. The company can use these insights to optimize their marketing strategy and maximize their return on investment.

