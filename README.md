# MLD_Econometrics
Econometric Analysis Mortgage Lending Discrimination

### Prerequisite
R

### Data
The original data from Home Mortgage Disclosure Act (HMDA) has 1990 observations with seven variables providing several demographic characteristics of the applicants and one variable for approval status. This dataset consists of Black, Hispanics, and random sample of White mortgage lending applicants of the Boston area in 1990. Since there were about 94% of Boston residents at the time were White, Black, or Hispanic, the dataset doesn’t include any other minority groups.

Descriptive statistics full data set

![image](https://user-images.githubusercontent.com/55430338/77610455-fd05ce80-6edf-11ea-8df1-f408f7bed631.png)


 Descriptive Statistic Summary by Race and Ethnicity
 
 ![image](https://user-images.githubusercontent.com/55430338/77610517-27f02280-6ee0-11ea-8d3f-e0e9936ceaca.png)
 
## Intro
In this study, we were able to obtain mortgage lending data for Black, Hispanic, and a random sample of White applicants of the Boston area for the year 1990. We found that White applicants were able to put down more down payment than the minorities applicants (on average, White applicants have 25% down payment while Black applicants only have 16% and 15% for Hispanic). This could explain the high approval rate of 90% among White applicants compared to an approval average of only 76% for Hispanic and 67% for Black applicants. However, our models suggest between applicants who have the exact same characteristics other than being White or minority, the predicted probability of getting approval for White applicant is still higher. 

## Model

Table1: Comparing Full and Minimized Probit and Logit Models

![image](https://user-images.githubusercontent.com/55430338/77610550-40f8d380-6ee0-11ea-9ed9-9266559736f9.png)

Table2: Comparing Full Model Results between Probit and Logit Models

![image](https://user-images.githubusercontent.com/55430338/77610590-5bcb4800-6ee0-11ea-8ee5-c8de520951b9.png)

Tabl3: Full Logit Model Resuts ~ Odds

![image](https://user-images.githubusercontent.com/55430338/77610787-ed3aba00-6ee0-11ea-8742-66b8bc4f6710.png)

Table4: Comparing Logit and Probit Probabilities

![image](https://user-images.githubusercontent.com/55430338/77610877-25da9380-6ee1-11ea-9049-b775ba034e71.png)


## Conclusion
Our models result suggest that there is a serious gap for the predicted probability of getting approval between White applicants and Black or Hispanic. Since our data doesn’t include any other minority groups except Black or Hispanic. Our data is lacking to create a broadly applicable model. Including only African Americans and/or black and Hispanics and/or Latinos limits the applicability of our model though not the results. Applicants that are white are given some form of preference over their two non-white ethnics and racial counterparts in our study. Via other literature in this area it is clear our conclusions align with studies that were able to include observations of Asian descent and a gap would indeed extend to individuals of Asian descent.
Although there have been many federal regulations against mortgage lending discrimination, we are still seeing the statistics trend from the 90s present now in 21st century.
