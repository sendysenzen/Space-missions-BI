# Space-missions-BI
BI Monthly Challenge from Maven Analytics

source data from : https://www.mavenanalytics.io/data-playground 
pick the August 2022 one

## SUMMARY & APPROACH

ETL was done using Power Query and based on real world information such as the country of certain launch location. Some data analysis was done with PostgreSQL (PgAdmin14). 
More than 50% of the records doesnt have the pricing data. Since it is difficult to obtain the data outside of the datasets, I didn't touch the rocket price in the summary. 
Biggest unfortunate is that also I couldn't get the company country data. That would be a lot work to do to check each company. If only I could get the data then the insight could be expanded more with many interest points. 
I didnt take the general knowledge or history such as milestone to be presented in the dashboard. My focus in the insight that can be explained by the provided data. Specifically I wanted to know the rocket activity. 
In the reality, the example of this insight, such as, which rocket has longest age, can explain certain company approach in executing the missions, or managing the rocket. For example, on the top 10 rockets with longest duty period, the list was dominated by RVSN USSR (which was owned by Russia). From this insight we could wonder and ask why they chose to maximize the utility of their rockets. Was their technology that different from the other? Or could be their missions goal is different than the other, so that they didnt require to utilize newer rocket with newer technology? 


Interactive Dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiOGNiZGYzZGUtMTYyZi00NzU4LThkYjAtYWNmMDcyYjgyZmFlIiwidCI6IjFhNGNiYmNlLWE5ZmItNGQyYS05MTU3LTBlMzlhNWNhMjc1MSIsImMiOjh9&pageName=ReportSection)

![Screenshot submission 2](https://user-images.githubusercontent.com/71933300/185988513-9bf170cd-0ca6-4369-a54b-ffca1a000d98.jpg)
