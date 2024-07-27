### Project Description

I am an analyst at Megaline, a telecommunications company offering two prepaid plans: Surf and Ultimate. The advertising department wants to determine which plan generates more revenue to adjust the advertising budget accordingly. 

**Objective:** Analyze a sample of 500 Megaline clients to identify which prepaid plan—Surf or Ultimate—brings in more revenue. The dataset includes client details, package type, and usage information (calls, messages, and data) for 2018.

**Prepaid Plan Details:**

- **Surf:** $20/month, 500 minutes, 50 SMS, 15 GB data. Overages: $0.03/min, $0.03/SMS, $10/GB.
- **Ultimate:** $70/month, 3000 minutes, 1000 SMS, 30 GB data. Overages: $0.01/min, $0.01/SMS, $7/GB.

**Instructions:**

1. **Data Preparation:** 
   - Load and examine data from various files.
   - Convert data types, clean errors, and decide how to handle missing values (e.g., 0.0-minute calls).

2. **Data Analysis:** 
   - Compute monthly call minutes, SMS count, and data volume for each user.
   - Calculate monthly revenue based on usage and package details.

3. **Behavior Analysis:** 
   - Describe consumer behavior, including usage patterns and revenue averages.
   - Create histograms to visualize the distribution of minutes, messages, and data usage.

4. **Hypothesis Testing:**
   - Test if the average revenue differs between Ultimate and Surf users.
   - Compare revenue from users in NY-NJ with other regions.
   - Formulate and test null and alternative hypotheses with a chosen alpha level.

5. **Conclusion:** 
   - Summarize findings and insights in a Jupyter Notebook, with code and explanations formatted properly.

**Data Description:**
- **Users Table:** Contains user IDs, names, age, subscription dates, churn dates, city, and plan.
- **Calls Table:** Includes call IDs, dates, durations, and user IDs.
- **Messages Table:** Contains SMS IDs, dates, and user IDs.
- **Internet Table:** Includes session IDs, data used, dates, and user IDs.
- **Plans Table:** Details plan names, monthly fees, allocations, and overage costs.

This analysis aims to provide insights into which plan is more profitable and inform future advertising strategies.
