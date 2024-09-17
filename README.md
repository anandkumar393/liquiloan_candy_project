**Project Title : Uncovering Key Drivers of Chocolate Candy Bar Purchases
**
Objective : To identify the key factors influencing the purchase of chocolate candy bars and generate actionable insights to optimize marketing strategies and improve sales performance.

Data Description

The dataset contains information on chocolate candy bar purchases made by 500 individuals over a period of 2 years in a specific area. The data was collected through the use of loyalty cards at checkout in a physical FMCG store. It includes details about each individual's purchasing behavior, such as the frequency and quantity of chocolate candy bar purchases, along with any other relevant attributes linked to their loyalty card usage.

This data provides insights into consumer buying patterns and preferences for chocolate candy bars.

Attribute Information:

ID

Shows a unique identificator of a customer.

Day

Day when the customer has visited the store

Incidence

Purchase Incidence
0 - The customer has not purchased an item from the category of interest
1 - The customer has purchased an item from the category of interest

Brand

Shows which brand the customer has purchased
0 - No brand was purchased
1,2,3,4,5 - Brand ID

Quantity

Number of items bought by the customer from the product category of interest

Last_Inc_Brand

Shows which brand the customer has purchased on their previous store visit
0 - No brand was purchased
1,2,3,4,5 - Brand ID

Last_Inc_Quantity

Number of items bought by the customer from the product category of interest during their previous store visit

Price_1

Price of an item from Brand 1 on a particular day

Price_2

Price of an item from Brand 2 on a particular day

Price_3

Price of an item from Brand 3 on a particular day

Price_4

Price of an item from Brand 4 on a particular day

Price_5

Price of an item from Brand 5 on a particular day

Promotion_1

Indicator whether Brand 1 was on promotion or not on a particular day
0 - There is no promotion
1 - There is promotion

Promotion_2

Indicator whether Brand 2 was on promotion or not on a particular day
0 - There is no promotion
1 - There is promotion

Promotion_3 :

Indicator whether Brand 3 was on promotion or not on a particular day
0 - There is no promotion
1 - There is promotion

Promotion_4

Indicator whether Brand 4 was on promotion or not on a particular day
0 - There is no promotion
1 - There is promotion

Promotion_5

Indicator whether Brand 5 was on promotion or not on a particular day
0 - There is no promotion
1 - There is promotion

Sex

Biological sex (gender) of a customer. In this dataset there are only 2 different options.
0 - Male
1 - Female

Marital_Status

Marital status of a customer.
0 - single
1 - non-single (divorced / separated / married / widowed)

Age

The age of the customer in years, calculated as current year minus the year of birth of the customer at the time of creation of the dataset
18 - Min value (the lowest age observed in the dataset)
75 - Max value (the highest age observed in the dataset)

Education

Level of education of the customer
0 - other / unknown
1 - high school
2 - university
3 - graduate school

Income

Self-reported annual income in US dollars of the customer.
38247 - Min value (the lowest income observed in the dataset)
309364 - Max value (the highest income observed in the dataset)

Occupation

Category of occupation of the customer.
0 - unemployed / unskilled
1 - skilled employee / official
2 - management / self-employed / highly qualified employee / officer

Settlement Size

The size of the city that the customer lives in.
0 - small city
1 - mid-sized city
2 - big city
