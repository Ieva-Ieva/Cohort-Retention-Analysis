# Cohort Retention Analysis of a Web Subscriptions-Based Company

## The aim of the analysis:																									
* to provide weekly subscriptions data that shows how many subscribers started their subscription in a particular week and how many remain active in the following 6 weeks;																									
* to show weekly retention cohorts for each week of data available in the dataset and their retention from week 0 to week 6.

## Tools used for the analysis:																				
* The data was extracted from the BigQuery using SQL
* The findings are visualised in [Tableau Public](https://public.tableau.com/views/M3_S1_ProjectbyIeva/RetentionDashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
<img width="875" alt="image" src="https://github.com/Ieva-Ieva/Cohort-Retention-Analysis/assets/96474283/a2290953-29e5-4f50-b5d2-69568e1714fe">

## The main findings:

1. **The total number of initial users who subscribe to the services each week is 274,362.**

2. **Subscribers used 3 types of connection devices, and the numbers of subscribers by each device differ greatly:**
   - **Desktop:** 158,917 users
   - **Mobile:** 109,195 users
   - **Tablet:** 6,250 users

3. **The overall subscribers’ behavior does not vary based on the device used:** users of all three devices maintain a retention rate of approximately 91%.
   - It’s interesting that the 20 December tablet cohort, as well as the 20 December and 27 December mobile and desktop cohorts, have the top retention rate (~97%) in week 1, which is the top retention rate for all users across all weeks.

4. **The average retention rates for each week show a gradual decline over time.**

5. **The highest retention rate is observed in December and January cohorts, while November cohorts show relatively lower retention.**

## Actionable Insights and Recommendations:

### 1. High Overall Retention Rate (The overall retention rate of ~91% is impressive, indicating strong subscriber loyalty and satisfaction) 

**Recommendation**: 
- **Enhance Engagement Strategies**: Continue implementing and enhancing engagement strategies that keep subscribers active. Consider introducing loyalty programs or exclusive content to maintain and potentially increase this high retention rate.

### 2. Device Usage and Retention (Subscribers use three types of devices (desktop, mobile, tablet), with desktop users being the largest group. Interestingly, the retention rate does not vary significantly across device types, maintaining a consistent ~91%)

**Recommendation**:
- **Optimize User Experience Across Devices**: Ensure the user experience is optimized for all devices. Since the retention rate is consistent across devices, maintaining a seamless experience on desktops, mobiles, and tablets is crucial. Regularly update and test the platform on all devices to prevent potential drop-offs.

### 3. Peak Retention During December and January (The highest retention rates are observed in the December and January cohorts, with the peak retention rate of 97% in week 1 for the 20 December tablet cohort and the 20 December and 27 December mobile and desktop cohorts)

**Recommendation**:
- **Leverage Seasonal Trends**: There seems to be a seasonal effect on retention rates. Leverage this trend by planning major marketing and promotional campaigns around these months. Consider offering special holiday promotions or discounts to attract new subscribers and retain existing ones.
- **Analyze Seasonal Content**: Investigate if any specific content or features introduced during these periods contributed to higher retention. Replicate or enhance these features in other months to boost retention.

### 4. Gradual Decline in Retention Over Time (The average retention rates show a gradual decline over the 6 weeks)

**Recommendation**:
- **Implement Re-engagement Strategies**: Develop and implement re-engagement strategies aimed at subscribers at risk of churning. This could include personalized email campaigns, push notifications, or in-app messages encouraging continued usage.
- **Feedback Loop**: Establish a feedback loop to understand why users drop off after the initial weeks. Conduct surveys or analyze user behavior data to identify pain points and address them promptly.

### 5. Discrepancies in November Cohorts (November cohorts show relatively lower retention rates compared to December and January)

**Recommendation**:
- **Investigate and Address Causes**: Conduct a deeper analysis to identify potential causes for the lower retention rates in November. This could involve examining external factors (e.g., less engaging content, fewer promotions) or internal factors (e.g., technical issues).
- **Targeted Interventions**: Implement targeted interventions for new subscribers during months with historically lower retention rates. This could include additional onboarding support, enhanced customer service, or special retention-focused promotions.																						
