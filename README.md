# MGT 4250 Course Project
Author(s): 
1. Ethan Singer (esinger5@elon.edu)
2. Brian Hunt (bhunt11@elon.edu)
3. Jalen Peoples (jpeoples@elon.edu)

## Project Description
This is the final project for course MGT4250 at Elon University. [Link to Visualizations](https://public.tableau.com/views/MGT4250_Final/Sheet1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link).

***Visualization 3 was unable to be deployed in Tableau Public due to clustering being unavailable, it will be included in the "Interpreting Visualizations" section and in the "MGT4250_Final.twbx" file.***
### Questions of interest
- What are the different segments of customers we have?
- How can we find the right customer segments to target our marketing efforts towards?
- How do the lifestyles of our customers influence their satisfaction and usage patterns?
  
### Importance
- Implement more clear and concise targeting objectives with improved customization efforts
- Increased operational efficiency
- DoorDash: “we can run an experiment and actually quantify the true impact that it had on the business… from a new
carousel on the home page to our release of the pickup map in the DoorDash app.”[^1]

## Data Description & Upload
We chose to use a dataset from an online food ordering platform. The data was
obtained in a csv format from the website Kaggle, and can be downloaded by clicking [here](https://www.kaggle.com/datasets/sudarshan24byte/online-food-dataset).

### Variable Explanation
- Age: Continuous variable that represents the age in years of the customer.
- Family size: Continuous variable that represents the number of individuals in the customer’s family. 
- Occupation: String variable based on the occupation of the customer (student, employed, housewife or self-employed).
- Feedback: Binary variable representing types of feedback with values of either positive or negative.

## Interpreting Visualizations

### Visualization 1
![Occupation Distribution](https://github.com/singere20/mgt4250spring2024/assets/55157734/8772f027-9e7f-49ff-8523-4b44848df633)

The first figure is a histogram titled “Distribution of Occupations”. This visualization
helps us understand our data and our customers better. By knowing occupation statistics,
we can start to make educated guesses on which occupation to target for marketing
purposes. Additionally, the breakdown of positive and negative reviews by occupation 
gives us some insight into how their employment status, and potentially,  their age,
is affecting their usage and satisfaction. Students (presumably younger people) are more
likely to order, and although they account for the second biggest portion of negative orders,
they still rank very high in customer satisfaction (85%). House wives, although only 
accounting for 9 of the orders, ranked similarly around 89%. People working at jobs
and self-employed people show the highest levels of dissatisfaction, and are just about
as likely to be unsatisfied (roughly 27.9% and 29.6%, respectively). Assuming that 
difference means anything, it may suggest that people who are more accustomed to needing 
to work with others often are more understanding of subpar service, or simply less likely
to report it.

### Visualization 2
![Age vs  Fam Size Scatter_Updated](https://github.com/singere20/mgt4250spring2024/assets/55157734/88b527f6-aa35-4c6a-875b-4748ccc9e001)

The second plot is a scatter plot with age on the x-axis, family size on the y-axis and
feedback as the color. This plot was created to see if there was any correlation between
age and family size. This would allow the marketing team to get an idea of the ideal
customer to target marketing efforts towards. Blink-182 notoriously claimed that "Nobody
likes you when you're 23," and if there is any truth to that statement, this data set 
supports it: 24-26 year olds are more likely than those younger than them and immediately
older than them to be unhappy with their order.Interestingly, this negative feedback does
spike back up again for some later ages. According to our sample, there is a direct 
correlation between being 30 years old and leaving a negative review.

Family sizes bigger than 1 but smaller than 4 are more likely to be dissatisfied with their order.
This could be indicative of the stress of starting a new family or marriage, as well as couples
with only children. It also could suggest that bigger families and single people should be the 
more heavily marketed towards than other groups. In fact, the optimal group to advertise to is a 
single person or a family of four, as there starts to be progressively more negative feedback as
the families get bigger, although it is still more positive than sizes 2 and 3.

### Visualization 3
![Symbol Cluster Map_Updated](https://github.com/singere20/mgt4250spring2024/assets/55157734/2152be34-6de4-4cef-8941-b1af3b0966b1)
<img width="409" alt="Screen Shot 2024-05-08 at 5 39 14 PM" src="https://github.com/singere20/mgt4250spring2024/assets/55157734/3ddebbbe-4d5c-48e5-826e-589acc4f8366">

The third graph is a symbol map displaying different clusters by color. The clusters
were made using the age, family size, and feedback columns. This is helpful to see
customers with similar demographics that responded positively or negatively to their order.
This further focuses our target market and gives us a profile of the typical customer who
responded well so that we can spend our effort and energy on specific groups of
customers.

## Discussion & Summary

Summary

The article from WSJ discussed how DoorDash has increased its use of analytics and forecasting to better understand and predict business outcomes in the face of economic uncertainty. Jessica Lachs, VP of Analytics, explains the analytics team focuses on a range of areas, such as pricing and order volumes, and item average per order (which she notes has been on the decline), to improve financial operations and decision making. This approach has become increasingly important due to impacts of inflation and changes in consumer spending habits. Notably, DoorDash has recently developed its own pricing index to better understand pricing on its platform.

Here were ChatGPTs responses to our three main questions that we sought to answer, given our visualizations and discussion for context:

“Certainly! Let's address each of your specific questions based on the provided visualizations and data analysis:
Questions and Answers
1. What are the different segments of customers we have?
Based on the visualizations and data:
•	Occupation: Your customer base includes employees, housewives, self-employed individuals, and students. Each of these groups has distinct patterns of feedback that can be used to segment them effectively for targeted marketing.
•	Age and Family Size: Your data also suggests segmentation by age and family size, with distinct patterns in feedback and preferences. For example, younger individuals (around ages 24-26) and families of size 2-3 show unique satisfaction and dissatisfaction trends.
2. How can we find the right customer segments to target our marketing efforts towards?
To find the right customer segments:
•	Positive Feedback Focus: Target students and individuals with positive feedback trends for loyalty programs or specialized promotions, as these groups have shown higher satisfaction.
•	Occupation-Based Targeting: Consider distinct marketing campaigns for different occupations; for example, offering special deals for housewives during off-peak hours or bundling offers for self-employed individuals who might need larger or more varied orders.
•	Age-Based Initiatives: Young adults showing negative trends might be targeted with new features or improved service to convert their experience to positive.
3. How do the lifestyles of our customers influence their satisfaction and usage patterns?
Lifestyle influences:
•	Occupation Influence: Employees and self-employed individuals show a higher dissatisfaction possibly due to their busy schedules and higher expectations. Tailoring services that cater to their time constraints and quality expectations could improve satisfaction.
•	Family Size Influence: Larger family sizes correlate with negative feedback, potentially due to the complexity of orders and higher expectations with larger orders. Ensuring accuracy and speed in these orders can mitigate dissatisfaction.
•	Age Influence: Young adults, particularly around age 30, show specific dissatisfaction, which could be addressed by examining what changes in service or product offerings could better meet their needs.

Conclusion

The combination of demographic, occupational, and lifestyle data provides a comprehensive view of how different segments of your customer base interact with your service. Targeted marketing efforts should focus on these aspects to optimize satisfaction and improve overall efficiency. This approach is in line with industry practices, such as those described in the DoorDash article, emphasizing the use of detailed analytics to tailor business strategies to customer needs.”

We feel that the project provides some insight into user likelihood and behavior, and trying to infer possible target segments based on what we find, much like DoorDash does in the article. However, we do feel that, if we had a better personal understanding of the economy of the country, or maybe scaled value for wealth that accounts for currency and samples across countries, that we would be able to have more insight into the income data. However, this can be hard to analyze ethically and in general, especially for self employed and other industry specific jobs.

When we provided GPT with the article, our visualizations, and discussion, it generally agreed over several responses:

“…These insights form a robust basis for targeted marketing strategies, aligning with the data analytics insights similar to the strategies used by companies like DoorDash, as discussed in the WSJ article. By understanding these segments and their unique needs or dissatisfaction points, you can tailor marketing efforts more effectively, potentially increasing customer satisfaction and retention.”

“Our visualizations align well with the insights from both the WSJ article and the generative AI's response. The clustering and demographic analysis show that specific segments, like students and smaller families, do have distinct patterns of feedback which can be leveraged to improve service and targeting. The WSJ article's emphasis on using analytics to adapt to customer needs and economic conditions reflects in our approach to using data-driven strategies to target customer segments more effectively.”

Additionally, we took the time to ask GPT what other questions it would have asked based on the article. Here are some of the ones we thought were worth mentioning:

1.	Impact of Analytical Features: "How might DoorDash's introduction of new product features and machine learning algorithms specifically enhance their financial forecasts and investment decisions?"
2.	Economic Indicators: "In what ways does the DoorDash item price index provide a more accurate or beneficial measure of economic impact compared to traditional economic indicators like the U.S. consumer price index?"
3.	Consumer Spending Trends: "Considering the shift in consumer behavior to fewer but higher-priced items, what strategies could DoorDash implement to maintain or increase order volumes during economic downturns?"
4.	Cost-Saving Measures: "What specific quality improvement measures could DoorDash focus on to reduce defects and refunds, and how might these impact their overall financial health?"
5.	Analytics in Different Business Lines: "How does the application of analytics to the grocery business line differ from its application in other areas of DoorDash’s operations, and what has been learned from these differences?"
6.	Future Projections: "Based on current analytics and market trends, what are some potential future challenges DoorDash might face, and how is the analytics team preparing to address these?"

Here were its answers:

1.	Impact of Analytical Features:	"DoorDash's use of new product features and machine learning algorithms allows for real-time, data-driven decision-making, enhancing financial forecasts and investment decisions. By quantifying the impact of these features, DoorDash can optimize its resources and tailor its offerings to meet changing market demands, potentially increasing customer engagement and revenue."
2.	Economic Indicators:	"The DoorDash item price index provides a tailored view of economic impact by focusing on consumer behavior specific to their platform. This index is beneficial as it reflects real-time changes in consumer spending on the platform, which can be more immediately indicative of economic trends than broader indices like the U.S. CPI, allowing for quicker strategic adjustments."
3.	Consumer Spending Trends: "To maintain or increase order volumes during economic downturns, DoorDash could consider strategies such as introducing budget-friendly options, promotional discounts, or loyalty programs. Tailoring marketing to emphasize the value and convenience of higher-priced items might also help sustain revenue even with fewer items per order."
4.	Cost-Saving Measures:"DoorDash could focus on enhancing the accuracy of its inventory and delivery systems to reduce defects and refunds. Implementing advanced predictive analytics to forecast demand more accurately and optimize supply chain logistics could lead to significant savings and improve margins."
5.	Analytics in Different Business Lines:	"The application of analytics in DoorDash's grocery business involves specific challenges like inventory management and product availability that are less prevalent in restaurant deliveries. Insights gained from focusing on these aspects have led to strategies that ensure item availability, which is crucial for customer retention in the grocery segment, differentiating it from other business lines."
6.	Future Projections: "Potential future challenges for DoorDash include increased competition, changes in consumer preferences, and regulatory challenges. The analytics team can prepare by enhancing their predictive capabilities to better forecast these trends and by continuing to innovate in areas critical to customer satisfaction and operational efficiency."

***I have left the part  my team members did to account for my error for your discretion below:

We chose to look at an article about how restaurants on Doordash can use customer analytics to increase sales. There are several benefits to using these insights including an increase in sales, customers acquired, brand loyalty, improved guest experience, optimized menus, and maximized marketing efforts. The article then goes through and talks about how to collect their data to run an analysis. Doordash allows businesses to see what percentage of customers are new, occasional, and frequent customers, as well as showing visual heatmaps based on which zip codes have the most orders.

https://get.doordash.com/en-us/blog/customer-analytics-for-restaurants

https://chatgpt.com/share/f5e5dbab-b716-4111-b46e-e2cf43300ecf?oai-dm=1

The article and ChatGPT’s content align fairly well with our observations. We used different analytical and visualization techniques to find the best customer segment to find out which market to target. We also found out which customer segments we are serving and whether they are mostly giving positive/negative feedback. We can use these results to help focus on certain target markets, and what characteristics they have in common.


[^1]:Mark Maurer “How Doordash Uses Analytics and Forecasting amid Economic Uncertainty.” (Wall Street
Journal, Dow Jones & Company Inc., 2023)
