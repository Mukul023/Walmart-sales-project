# Walmart-sales-project
 Walmart is a renowned retail corporation that operates a chain of hypermarkets. Here, Walmart has provided a data combining of 45 stores including store information and monthly sales. The data is provided on weekly basis. Walmart tries to find the impact of holidays on the sales of store.
## Problem :
There are many seasons that sales are significantly higher or lower than averages. If the company does not know about these seasons, it can lose too much money.
## Aim :
Our Main Objective is to predict sales of store in a week. As in dataset size and time related data are given as feature, so analyze if sales are impacted by time-based factors and space- based factor. Most importantly how inclusion of holidays in a week soars the sales in store?
## Plan:
- Understanding, Cleaning and Exploring Data
- Preparing Data to Modeling
## Findings:
- Although some departments has higher sales, on average others can be best. It shows us, some departments has effect on sales on some seasons like Thanksgiving.
It is same for stores, means that some areas has higher seasonal sales.
- Stores has 3 types as A, B and C according to their sizes. Almost half of the stores are bigger than 150000 and categorized as A. According to type, sales of the stores are changing.
- As expected, holiday average sales are higher than normal dates.
- Top 4 sales belongs to Christmas, Thankgiving and Black Friday times. Interestingly, 22th week of the year is the 5th best sales. It is end of May and the time when schools are closed.
- Christmas holiday introduces as the last days of the year. But people generally shop at 51th week. So, when we look at the total sales of holidays, Thankgiving has higher sales between them which was assigned by Walmart. But, when we look at the data we can understand it is not a good idea to assign Christmas sales in data to last days of the year. It must assign 51th week.
- January sales are significantly less than other months. This is the result of November and December high sales. After two high sales month, people prefer to pay less on January.
- CPI, temperature, unemployment rate and fuel price have no pattern on weekly sales.
More detailed finding can be found in notebooks with explorations.

## Future Improvements:

- Data will be made more stationary with different techniques.
- More detailed feature engineering and feature selection will be done.
- More data can be found to observe holiday effects on sales and different holidays will be added like Easter, Halloween and Come Back to School times.
- Markdown effects on model will be improved according to department sales.
- Different models can be build for special stores or departments.
- Market basket analysis can be done to find higher demand items of departments.
