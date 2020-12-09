# Comparing Employment Rate in Baltimore City, MD and Washington D.C. with Opportunity Atlas Data

## Background
Employment rate is used to analyze the social and economic health of neighborhoods and cities. While this is not the only tool to determine social welfare, it is one of the oldest and easiest tools to analyze. High employment rates are typically associated with prospering communities while low employment rates are associated with crime and instability. 

President Trump frequently cites lowest black unemployment rate as an achievement for his presidency. However, this fails to properly determine the economic health of black communities in the United States cities. Although highest black unemployment rate is an achievement, it may not seem as monumental when compared with the unemployment rate of their white neighbors.

This project will investigate and compare the employment rate for black and white residents of Washington D.C. with their peers in Baltimore, MD. The data will be extracted from Opportunity Atlas, an online database that tracks millions of Americans from childhood to adulthood. 


## Business Question
How do the employment rates of black and white residents in Washington D.C. and Baltimore, MD compare?

## Data Source
https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/Opportunity%20Atlas%20Data.xlsx
All data was collected from the Opportunity Atlas Database. The database collected information on individuals from several neighborhoods across America ranging from income to employment rate. 

## Data Analysis (Excel)

![alt text](https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/Blacks%20vs%20Whites%20Employment%20DC.png)
- Slightly higher employment rate in whites than blacks. 
- Noticable disparity in low employment rates between blacks and whites 

![alt text](https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/Blacks%20vs%20Whites%20Employment%20Baltimore.png)
- Similar employment rate in each neighborhood 

![alt text](https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/Average%20Employment%20Rate%20of%20DC%20White%20vs%20Baltimore%20White.png)
- Highest employment rate are very similar once again
- Lowest employment rates are significantly lower for Baltimore than D.C.

![alt text](https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/Average%20Employment%20Rate%20of%20DC%20Black%20vs%20Baltimore%20Black.png)
- Baltimore neighborhoods have both the highest and lowest employment rate

## Summary 
- It can be concluded that Baltimore black neigborhoods exhibit the greatest range in employment rate. 
- The majority of comparisons also show similar rates of high employment and greatest disparities at lower employment rates.
- Baltimore neighborhoods recorded the highest employment rates. 
- Employment rate may not be the best representation of social welfare. 

## Data Analysis (Python)
- In addition to analyzing the Baltimore and DC employment data through Excel, we also used Python for additional visualizations. Our primary goal in doing this is to compare Python with Excel as analytical tools. Using plotly express, I constructed bar graphs to compare average employment rates between blacks and whites in Baltimore and DC. In addition, I wanted to create a combined bar graph to compare the four averages.

![alt_text](https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/AverageEmploymentinBaltimoreBar.png)
- Employment rates between blacks (73.6%) and whites (73.3%) are close in Baltimore.

![alt_text](https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/AverageEmploymentinDCBar.png)
- The disparity in average employment rates between blacks (74.8%) and whites (78.9%) is noticeably greater in DC than Baltimore. 

![alt_text](https://github.com/yoselassie99/baltimore-washingtondc-employmentrate-data/blob/master/AverageEmploymentRateinBaltimoreandDC.png)
- Comparing average employment rates for each racial group between cities, we see DC blacks and whites have higher average employment rates than Baltimore blacks and whites, respectively. In general, it can be concluded that DC has higher average employment rate than Baltimore.

## Discussion on Use of Python
I wanted to compare and analyze average employment rates since it was not included in my mini-project 1. Additionally, a visualization representing average employment rates is a more condensed visual than the bar graphs used in mini-project 1. Through this mini-project, I gained my first experience using Python for data analysis. Although I struggled at times, there were clear benefits with using Python over Excel. Specifically, I found data cleaning and merging to require significantly less steps. With data merging, using tract numbers to combine datasets was a more efficient method than the manual merging employed for Excel analysis. However, this strength became a weakness when trying to compare average employment rates in racial groups. Since Baltimore Blacks did not share tract numbers with DC Blacks, I was unable to merge the datasets and did not have a data visualization to represent the different average employment rates. Instead, I combined the Baltimore and DC bar graphs so all four average employment rates could be presented in a singular visualization. 

In conclusion, I still believe employment rate data does not properly represent social welfare in communities. For example, the similar average employment rates between Baltimore blacks and Baltimore whites does not mean the quality of life is also similar, as additional factors such as household income and population size for each neighborhood helps paint a more complete picture. 
