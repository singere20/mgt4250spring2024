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
likely order, and although they account for the second biggest portion of negative orders,
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
supports it: 24-26 year olds are more likelythan those younger than them and immediately
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

We chose to look at an article about how restaurants on Doordash can use customer analytics to increase sales. There are several benefits to using these insights including an increase in sales, customers acquired, brand loyalty, improved guest experience, optimized menus, and maximized marketing efforts. The article then goes through and talks about how to collect their data to run an analysis. Doordash allows businesses to see what percentage of customers are new, occasional, and frequent customers, as well as showing visual heatmaps based on which zip codes have the most orders.

[Link to conversation with ChatGPT](https://chat.openai.com/share/f5e5dbab-b716-4111-b46e-e2cf43300ecf)

The article and ChatGPT’s content align fairly well with our observations. We used different analytical and visualization techniques to find the best customer segment to find out which market to target. We also found out which customer segments we are serving and whether they are mostly giving positive/negative feedback. We can use these results to help focus on certain target markets, and what characteristics they have in common.




[^1]:Mark Maurer “How Doordash Uses Analytics and Forecasting amid Economic Uncertainty.” (Wall Street
Journal, Dow Jones & Company Inc., 2023)
