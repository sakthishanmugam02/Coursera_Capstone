# Battle of Neighborhoods -Project

## Introduction
_This is an assignment as part of the Capstone Project which is part of the IBM Professional Data Science Course._

The task is to explore location data, find an imaginary problem that could be solved using available information and produce the result by extracting out required information using appropriate python data science libraries and methodologies. 

### Problem Statement
>Need effective advice to identify best kind (categories - Men's, Women's and Kids) of Clothing Store that can be opened in New York City. 

#### Background
One fine day, one of my close friends came to me and said, he had won the lottery ticket and would like to spend half of the money to charity and with the remaining amount he would like to invest in a clothing shop in New York. I congratulated him and encouraged his idea of opening the shop and suggested him to go ahead. Then our discussion went further on exploring different categories of clothing shops (such as Women's, Men's and Kids). Suddenly we started puzzling about how many shops are there in each category and what are the people's interests? and so on. We don't have any clue at all of these facts. But we realized one thing that all these data are very much important. 

#### Idea
Time was ticking and we had no clue on how to collect these data and solve the problem, then we decided to call our friend (Ankur) who was working as a Data Analyst. We explained the full details. He replied that he could help us by analyzing the data available on the Internet and also he ensured he would come up with the required information in a presentable format so that we could also understand his analysis in a simple manner. 

### Initial Analysis
Ankur started researching the data required to identify the best kind (categories - Men's, Women's and Kids) of Clothing stores that can be opened in New York City.

The followings are the list of data he shortlisted to figure out the answer.


| <p align="left"> Data </p> | <p align="left"> Purpose </p> |
| ----| ----|
| <p align="left"> Coordinates of New York Neighbours </p>   | <p align="left"> To plot the map to explain shops located in various places visually, so that his friends can grasp it easily. <br> Required data is available here in this link.https://cocl.us/new_york_dataset </p> |
| <p align="left"> List of venues | <p align="left"> To explore the lists of venues near to their city. <br> Use following Four Square API to get these data <br> https://api.foursquare.com/v2/venues/explore?&client_id={}&client_secret={}&v={}&ll={},{}&radius={}&limit={} <br> This would help in getting the list of shops and its location. </p>  |
| <p align="left"> Categories field in the previous API response </p> | <p align="left"> This would help in filtering only the shops required.</p>|
| <p align="left"> Details of venue </p> | <p align="left"> Use Four Square API which is there in following link <br> https://developer.foursquare.com/docs/api/venues/details <br> This would help in getting people's interest in various shops and their shopping time patterns and so on. </p> |

__Note:__ <br>
_Analyzing the data through various visualization approaches of data science methodology using appropriate python library is part of Ankur's plan_

***
<p align="center"> END-OF-PROBLEM-STATEMENT </p>

***

## Exploratory Data Analysis

### Statistical data of shop based on its category. 
#### Observation and analysis based on the above results are as follows:
With these data, we are sure that there are very few options for Kids Clothing across the Manhattan region. 

_It could be a good idea if our boss's friend opens up a Kids Store._

There are already quite a few shops that are there for Women's and Men's. So, if they open up a new shop in those categories, then they might end up facing heavy competition from others. 

**"Less competition, lesser the risks".** Also, with our boss previous project, he is aware that there are many kids in that region. That could pull the crowd. 
 ![Alt text](https://github.com/sakthishanmugam02/Coursera_Capstone/blob/master/BarChartOnShopCountBasedOnCategory.png "Shop count based on category")

#### Based on the available information so far.
We can assure our friends that both the shop's popularity is on average (around 6-7). 
Only very few people have liked it too.  

##### The popularity of existing shops
 ![Alt text](https://github.com/sakthishanmugam02/Coursera_Capstone/blob/master/popularity-table.png "The popularity of existing shops")

##### The Popularity Analysis
 ![Alt text](https://github.com/sakthishanmugam02/Coursera_Capstone/blob/master/popularity-bar.png "The Popularity Analysis")

#### Findings:
So far, we figured out opening a Kids shop is a much better option compared to other Clothing categories since competition is very less. Plus, two shops that are located in the Kids category is received lesser popularity. With a good marketing strategy, it is easy to reach people's knowledge. 

## Conclusion:
Based on the analysis, we would recommend our friends to start a Kids Store in Manhattan, New York City. 

## Future Directions:
The recommendation is to start exploring the right options to marketing channels. Let's try to win people's hearts.
