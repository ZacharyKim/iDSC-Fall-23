# Illinois Data Science Club Spring 2023 Team Avalanche Project

## Introduction
- U.S. job market shaped by economy, society, and tech.
- COVID-19 emphasized sector resilience, especially in tech.
- Remote work and innovation became crucial.
- Economic, social, tech, and global factors influence employment.
- Key for success: Adaptability, digital literacy, continuous learning.


## Goals
- Forecast next year's employee rate for 76 Fortune 500 companies. This information helps a company understand how financial decicisons effect their employees
- Show how different sectors have perfomred within the past few years. This information helps job seekers find a sector that will keep them instead of laying them off
- Project shows how the employment rate for each company and industry sector has increased/decreased based on financial performance, size of company, location and other inter-company decisions.

## Roadblock
we origanlly wanted to do tech layoff rates and how a company's finances effects those rates. However after merging and cleaning the two datasets there only seven companies so we changed our project idea to overall employee rates based off of 76 randomly chosen fortune 500 companies

## Methodology
1. searched for database
2. cleaned the databse
3. analyzed dataset/ made visuals
4. exploratory data analysis
5. interpreting meaning behid the desceiptive states
6. conclusion
  

## Data Dictionary
  - company: the name of the company <br>
  - location: the headquarter state of the company <br>
  - industry: industry that the company belongs to <br>
  - sector: financial sector that the company belongs to <br>
  - employees_gained: the number of employess a company has gained or lost in the given year <br>
  - employment_change_rate: the percent of employees that a company gained or lost in a given year <br>
  - total_equity_mil: the total amount of equity a company has gained from its stakeholders in a given year in millions of USD <br>
  - total_revenue_mil: the total amount of revenue a company has gained in a given year in millions of USD <br>
  - total_employees: the total amount of employees a company has in a given year <br>
  - profit_mil: the total amount of profit a company has gained or lost in a given year in USD <br>
  - relocation: whether a company relocated in a given year <br>
  - mergers_buyouts_acquisitions: whether a company merged, was boughtout, or aquired companies in a given year <br>
  - year: the year that the data pertains to <br>
  
## Analysis
<ins>Research Question: How has employment changed overall within the past few years? <br>

**Purpose:** Helps show how the economy is changing 

![image](https://github.com/ZacharyKim/iDSC-Fall-23/assets/43355013/136b6fbc-919a-4e49-bfb4-82609d22fdf2)


**Conclusion:** <br>
From this data, we can see that there is a larger spread in 2020 and 2021 compared to 2022. This is due to companies having varying repsonses due to COVID-19. As the years go on, the median value goes up a tiny bit.

![image](https://github.com/ZacharyKim/iDSC-Fall-23/assets/43355013/d05bb566-62ec-4d25-ae07-ea754461ccfa)
From this data, we can see that there were a large amount of employees layed off in 2020. This is due to many companies having to layoff employees due to COVID-19. The large dip in 2022 is mainly caused by the Amazin layoffs as they layed off 67,000 employees that year


<ins>Research Question: What sectors are the best to work in based on past few years data? <br>

**Purpose:** Helps job seekers to work in a sector that won't lay them off

![image](https://github.com/ZacharyKim/iDSC-Fall-23/assets/43355013/f71eb907-56af-49ba-a162-b4161c518b85)

**Conclusion:** <br>
From this data we can see that motor vehicle & parts has had the largest percent of employees gained and that telecommunications has layed off the most employess by percentage


<ins>Research Question: How do different factors effect employee change rates? <br>

**Purpose:** Shows how employee rate changes if only one predictor variable changes
![image](https://github.com/ZacharyKim/iDSC-Fall-23/assets/43355013/2ca43e4b-2c13-45b4-b6f2-84db98b457d9)

**Conclusion:** <br>
If only one variable changes while everything else stays the same then the employee rate doesn't change much. This means that there isn't one factor that causes a change in employment. The employee rate change is caused by a combination of all these factors combined

<ins>Research Question: How much impact do certain factors have on employment rates? <br>
**Purpose:** Shows what factors impact employee rates the most

![image](https://github.com/ZacharyKim/iDSC-Fall-23/assets/43355013/17ab9539-461a-4788-8276-0fbe8d64404a)
![image](https://github.com/ZacharyKim/iDSC-Fall-23/assets/43355013/2cdcf7a3-82c4-42a4-9a07-03534b0c8caf)

**Conclusion:** <br> 
The location doesn't impact the change rate much. Based on our data, we found that if a company is in the vehicle & motor parts sector, then this company will impact employee rates in a positive way. This is due to Tesla gaining more employees every year since 2020. On the other hand, if a company is in the telecommunications sector, then it has a negative impact on the employee rates. This is due to AT&T laying off employees every year since 2020.
