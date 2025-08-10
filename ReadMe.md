# Bank churn customer analysis

## problem statment 

The Bank operates in 3 different countries in Europe namely; France, Spain and Germany. The bank is experiencing customer attrition (customer leaving) and needs to understand the underlying factors contributing to customer churn (customers going to other banks that perform the same operation. The goal is to analyze customer demographic (these are measurable traits and characteristics used by companies to attract customers these include age, income, gender, understanding the bank demographics will help them make better personalized marketing strategies and improve their banking offerings or services or product offering to better meet customer needs) , financial, and engagement data to identify patterns that distinguish loyal customers from those who leave. This analysis will support the development of targeted strategies for improving customer retention, engagement, and overall satisfaction.

In short: "Why are customers leaving the bank, and what can be done to reduce churn and improve customer engagement?"

## Objectives

Merge the data for customers and account information.

Examine and Profile the data.

Prepare for visualization.

Draw conclusions and recommendation.


## Data 

The data folder contains datasets from three different Barclays bank branches in Europe; France, Spain and Germany. Each data file from the branches contains the same attribute information and see below the attribute description.    

Customer ID: A unique identifier for each customer. 

Surname:  The customer’s last name. 

Credit Score: A numerical value representing the customer’s credit score. This is used by lenders to access your creditworthiness and decide whether to give you a loan or not.  

Geography: The country where the customer resides (France, Spain or Germany). 

Gender: The customer’s gender (Male or Female). 

Age: The customer’s age. 

Tenure: The number of years the customer has been with the bank. 

Balance: The customer’s account balance 

Number of Product: The number of bank products the customer uses (e.g., saving account, credit card, current account, loans, insurance, digital banking) 

Has credit card: whether the customer has a credit card. The numeric 1 means yes and the numeric 0 means no.  

Is active Member: whether the customer is an active member. The numeric 1 means yes and the numeric 0 means no. 

Estimated: The estimated salary of each customer.  

Exited: Whether the customer has churned. The numeric 1 means yes and the numeric 0 means no.  

## Insights

1.customer demographics insights. 

 churn by Gender. 

This plot helps identify which gender is more likely to churn. customers that are still in the bank are represented by the numeric 1 and customers no longer in the bank are represented by the numeric 0. 

This plot shows that female customers are likely to churn to the bank (0) and male customers are more retained. Although it should be noted that the difference is not substantial. 

This result might suggest a need for targeted retention strategies for both genders especially the female gender. 

 

Churn by Geography  

France has the largest customer base, but its churn count appears relatively lower compared to its size. 

Germany shows a higher proportion of churn, even though its total customer base is smaller. 

Spain appears more balanced. 

This suggests regional differences in customer satisfaction— Germany may need targeted customer retention strategies. 

Churn by age. 

The bank customers are between 30 and 40 years old, but churn is more frequent in older age category. 

There is a significant spike in churn among customers aged 40–60+, suggesting they may feel underserved or dissatisfied or inadequately attended to. 

This also suggests that the bank might give more products to younger customers making customers in this age bracket feel less appreciated. 

The lack of such incentives or attention might make customers in those age bracket opt for banks that tend to their age groups. As customers in those age brackets tend to be careful or mindful where they invest their money. 

Younger customers (under 30) are less likely to churn suggesting the bank needs more optimization or incentive or valuable products like insurance or loans that will encourage them to stay. 

This suggests to a possible need for age-centered engagement protocols or procedures, especially for older customer groups as this will affect the bank retention of those customers or even gaining them initially. 

This could affect the banks reputation / core values i.e discrimination in terms of age. 

 

2. financial standing insights. 

Account balance distribution by churn 

1 There's a large spike in churn (Exited = 1) at zero account balance. This suggests that many customers who churned were not actively using their accounts. The bank should improve onboarding, monitor account activation, follow up on dormant users 

2 Higher Balances = Lower Churn 

As the account balance increases, the number of churned customers decreases. Customers with substantial balances are more likely to stay loyal, possibly due to: Better service tiers, Higher investment in the relationship, Use of multiple products, the bank may offer more incentive/products offers to customers who have higher balances to prevent them from leaving. To retain customers, the bank should offer loyalty perks or benefits, personalized financial planning 

3. Mid-range Balances Show Mixed Behavior. In the middle of the distribution, churn exists but is less extreme. This segment may be more sensitive to customer experience or competitive offers from other banks. maybe the bank needs to review its products to target middle class earners and offers better customers experience. The bank should target them with retention campaigns or product cross-sell. 

 

Credit score distirbution by churn 

Even Distribution Across Credit Score. The chart shows that both churned and retained customers are spread across all credit score ranges.There’s no sharp peak or drop indicating a strong churn-driving credit score threshold. Creditworthiness alone doesn’t drive churn. 

Low Credit Score Does Not Guarantee Churn. Even customers with lower credit scores (below 500) are not drastically overrepresented among those who exited. 

High Credit Score Does Not Guarantee Loyalty. Surprisingly, high credit score customers (above 700) also show churn behavior. This suggests that trust or financial strength isn't enough to keep them — experience or product fit may matter more. Explore dissatisfaction with services or uncompetitive offerings 

 

Estimated Salary by churn 

 

Even Distribution Across Salary Ranges There doesn’t appear to be a strong correlation between estimated salary and churn. Both customers who churned and stayed are spread fairly evenly across salary brackets. 

Churn Occurs at All Income Levels High earners (e.g., salaries > €100,000) are just as likely to churn as low earners. Suggests that financial capacity alone doesn’t prevent churn. 

Middle Salary Brackets Show Slight Drop In some datasets, you might notice slightly lower churn in middle-income brackets (€50,000–€70,000), possibly due to balanced expectations. 

 

3. Engagement patterns insights. 

Churn count by active members.  

-non-active members in the bank tend to exist more than active members. This might be because of dissatisfaction from the bank or lack of attention to customer's service. 

1. Non-Active Customers Churn More. Customers who are not active members (value = 0) show a much higher churn rate. Indicates strong correlation between customer engagement and retention. 

  

2. Active Members Are More Loyal. Customers marked as active members (value = 1) churn significantly less. This suggests active participation or use of services is a protective factor against churn. 

 

Churn by tenure. 

Higher Churn at Mid Tenure. There's a spike in churn around 5–6 years of tenure. Suggests customer dissatisfaction or unmet expectations typically builds up during mid-term engagement. 

Lower Churn at Low and High Tenure. Customers with 1–2 years and 9–10 years of tenure show lower churn. New customers might still be exploring services. Long-term customers may feel committed or satisfied. 

Volatility Between Years. The churn rate isn't linear – it fluctuates, implying that other factors (e.g., product offerings, support experience) could influence decisions at certain tenure lengths. 

Churn by number of products.  

- The number of products does not have a correlation to whether a customer is being retained or not. 

- most customers who have purchased at least one or two products are still in the bank. 

- the bank need to understand why customers with 3 or 4 products leave. This can be because of poor loyalty points, customer service or lack of attention to details in the products given by the bank. 

- This also shows that customers buying more products does not guarantee retention because customer with one and two products tend to stay when compared to customers who bought 3 or 4 products. 

   

- This suggests the bank should focus of understanding why customers with one or two products tend to stay. 

- The bank need to set optimization strategy that will encourage customers who have one or two to buy more eg they can have loyalty perks. This is because customers with 3 or 4 seem to be dissatisfied with the product or customer service or lack of loyalty perks. 



## Recommendations

Demographics-Based Recommendations
Gender

Female are slightly more likely to leave. Create personalized offers for female customers. Collect feedback to understand their needs better.
Geography

More customers leave from Germany. Survey German customers to find out why. Offer local deals or improve customer support in that region.
Age

Older customers (40–60+) leave more. Offer age-specific products or services. Use loyalty programs and personal service to build trust.
Financial Standing-Based Recommendations
Account Balance

Many customers with zero balance leave. Follow up to get new users active. Reward high-balance customers to keep them loyal.

Credit Score

Churn happens at all credit levels. Focus on customer experience, not just credit score. Use credit score with other data to better predict churn.

Estimated Salary

Income doesn’t predict loyalty. Provide great service to all customers, not just wealthy ones.

Engagement-Based Recommendations
Active Membership

Inactive users churn more. Re-engage them with emails, offers, or benefits.

Tenure

Customers around 5–6 years are more likely to leave. Improve experience mid-way with special offers or check-ins.

Number of Products

Even customers with more products can churn. Understand why they leave. Make sure bundles offer real value and rewards.


## Conclusion.

Churn is caused by a mix of who the customer is, their finances, and how engaged they are.

Keep customers by focusing on personalized service and active engagement.
Don’t assume wealthy or long-term customers will stay—check in and offer value.
Retention is about building strong, ongoing relationships—not just getting sign-ups. 
