# Data-Analysis-of-National-Vaccination-Coverage-Estimates-of-Adolescents-Aged-13-17-years-in-SAS
Analyzed national vaccination coverage estimates focusing on adolescents aged 13-17

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methods](#methods)
4. [Data Analysis](#data-analysis)
5. [Tables Summary](#tables-summary)
6. [Conclusion](#conclusion)



## Introduction

The National Immunization Surveys (NIS) are a group of telephone surveys used to monitor vaccination coverage among teens. In NIS-Teen surveys, they dial random digit numbers in all 50 states, the District of Columbia, selected local areas, and some U.S. territories to ask Parents or guardians of eligible adolescents for an interview to gain sociodemographic information about the household, and to get permission to contact the adolescent’s vaccination provider. Then, they will send a questionnaire to the providers to receive the adolescent’s vaccination record. By receiving the immunization records, vaccination coverage estimates will be provided which include any vaccines administered before the 2021 NIS-Teen interview date. The report contains vaccination coverage estimates for 18002 adolescents aged 13–17 years. The analysis of weighted data for the complex survey design has been presented and T-tests were used to compare differences in vaccination coverage by survey year (2021) and among sociodemographic groups. Moreover, based on the p-value we can conclude that the data provide significant evidence that there is a difference between each category for the demographic information. So, if the p-value is less than 0.05, we can say that the test is statistically significant. In this project, all the data analysis has been conducted in SAS 9.4 Version. Also, the 2021 NIS-Teen data is included of 45036 teens with completed household interviews. Besides, we have used data for 18006 teens to determine the coverage estimates of the vaccine 1+ HUMAN PAPILLOMAVIRUS SHOT.

## Dataset 

Data: National Vaccination Coverage Estimates of Adolescents Aged 13-17 years by Selected Demographic and Access to Healthcare Characteristics Using National Immunization Survey – Teen (NIS-Teen), 2021 Public User Files (PUF).


## Methods

In this project, data analysis of the 2021 National Immunization Survey–Teen (NIS–Teen) has been performed based on the total sample size which is equal to 18,002. The goal of this survey is to provide information about vaccination coverage for all adolescents aged 13-17 years with adequate provider data (ADP) and to investigate demographic information. In this survey, the families with adolescents aged 13-17 years have been identified by conducting the random digit dial telephone interview. Also, demographic information from the parents of each family has been collected. The questions in the interview are about the adolescent vaccination history. If the adolescent received the HPV vaccine, then the interviewer will ask about the type of place where the adolescent received an HPV shot. Next, the interviewee needs to contact the vaccination provider after obtaining the parents’ consent. Then, they will send a questionnaire to the vaccination provider to obtain the required vaccination history for each recommended adolescent vaccine to determine the vaccination coverage estimates. All the data analysis has been conducted in SAS 9.4 Version.

## Data Analysis

-	All weighted percentages to 1 decimal place have been reported.
-	Histogram for the following variables: Age (years), Mother's Age, and Income to Poverty Ratio include weights have been presented.
-	Vertical Bar-Graphs for the following variables: Sex of Adolescent, Race/Ethnicity, Mother's educational level and Mother's marital status include weights have been presented.
-	Pie-Charts for the following variables: Medical insurance, Well Child visit at age 11-12 years, Census Region based on true state of residence and Vaccination Facility Type include weights have been presented.
-	All chi-square test statistics and their corresponding p-values to 2 decimal places in Table 2 have been reported.
-	We Indicated which variable or variables are associated with the type of vaccination for your group.
-	Unweighted sample sizes and weighted percentage to 1 decimal place in Table 3 have been reported.
-	Table 4 has been provided by using PROC SURVEYFREQ.
-	Unadjusted weighted vaccination coverage estimates for all the selected variables in Table 5 have been presented by using PROC SURVEYMEANS.
-	Unadjusted ODDS RATIOS to 2 decimal places for all the selected variables in Table 5 have been presented by using PROC SURVEYLOGISTIC.
-	Adjusted ODDS RATIOS to 2 decimal places for all the selected variables in Table 5 have been presented by using PROC SURVEYLOGISTIC.
-	Adjusted ODDS RATIOS to 2 decimal places for all the significant selected variables in Table 5 have been presented by using PROC SURVEYLOGISTIC.
-	Type III test of effect for models 3, 4, and 5 in Table 6 has been reported. All Wald Chi-Square test statistics to 3 decimal places and their corresponding p-values to 2 decimal places have been reported.


## Tables Summary

TABLE 1. Sample Characteristics of Adolescents Aged 13-17 Years in the United States, by Selected Demographic and Access-To-Care Variables--NIS-Teen 2021

TABLE 2. Vaccination Coverage Estimates Amongst Adolescents Aged 13-17 Years in the United States, by Selected Demographic and Access-To-Care Variables--NIS-Teen 2021

TABLE 3. Vaccination Coverage Estimates Amongst Adolescents Aged 13-17 Years in the United States and by States --NIS-Teen 2021

TABLE 4. Sample Characteristics of Adolescents Aged 13-17 Years in the United States, by Selected Demographic and Access-To-Care Variables--NIS-Teen 2021

TABLE 5. Vaccination Coverage Estimates Amongst Adolescents Aged 13-17 Years in the United States, by Selected Demographic and Access-To-Care Variables--NIS-Teen 2021

TABLE 6. Type III Test of Effect for Models Using NIS-Teen 2021.


## Conclusion


In this project, the analysis of (NIS-Teen) 2021 data with the focus vaccine as 1+ HUMAN PAPILLOMAVIRUS SHOT(P_UTDHPV) and with a total of 18002 participants has been presented. Also, the histograms, bar charts, pie charts and tables have been provided. First, we presented the histograms of the percentage of participants at interview by age, by adolescent mother’s age, and income poverty ratio. As can be seen from the graphs, we can conclude that most of the mothers’ age at interview are greater than 35 years and just 6.8 % of the mothers who responded are less than 34 years old. Moreover, there is a significant difference between the two income-poverty ratio categories (0% to <133% and 133% to 322%). We can say that high-income respondents are more than two times higher in percentage than lower-income families, so it means that the low-income mothers did not respond very often at the interview. Also, the histogram using age at the interview shows that the teens’ age which has been equally distributed. 

Based on the bar charts, we can see that the number of the male respondents (51.0%) is larger than female (49.0%) with a narrow margin. Also, we can conclude that non-Hispanic white responses to vaccination interview are more than 3 times of other races which means that non-Hispanic white people preferred to have the interview rather than other races (non-Hispanic black only, Hispanic and non-Hispanic other plus Multiple race). Besides, we can see that the education has a huge effect on the number of people who responded to the interview. As can be seen, the more educated the mothers are, the more interested in having the vaccination interview. Also, the percentage of married mothers (62.5%) is twice larger than others (never married/ widowed/ divorced/ separated/ deceased/ living with partner (37.5%)).
The first pie chart that has been presented is about the medical insurance of the adolescent which shows that private insurance (55.0%) and any medicate (35.3%) have the larger portion compared to other categories. It is clear from the information given in the pie chart of the well child visit at age 11-12 years old of the adolescent that 81.5% of the adolescent age 11-12 like to do the check up which is significantly higher percentage compared to the ones who do not checkup. The evidence from the third pie chart (the census region of the adolescent) indicates that the most frequent census region is the south (39.3%) of the United State and the second most frequent is the west (24.2%). On the other hand, the northeast is the least frequent census region with 15.6%. The last pie chart is about the vaccination facility of the adolescent which shows that 41.5% of the vaccination facility is related to the private facilities. However, the vaccination facility in the school/teen clinic section was just 2.2% which is very low compared to others. Overall, we can conclude that most of the participants in this survey were more to be male, white, with higher household income, with health insurance, and with more educated mothers.

In this project, we presented 6 tables. Table 1 provides information about the sample sizes and the weighted percentages for each demographic category which have been interpreted by graphs. From the information shown in the table 2, we presented the vaccination coverage estimates amongst adolescents aged 13-17 years in the United States, by selected demographic and we considered the 1+ HUMAN PAPILLOMAVIRUS SHOT as the vaccine type. In this table, the sample size, the weighted 95% confidence intervals, chi square statistics and p value for every demographic category have been presented. As can be seen from the results, in every demographic, P-value are 0 (which are less than 0.05), so we got significant confidence intervals. As shown in the table 3, vaccination coverage estimates amongst adolescents aged 13-17 years in the United States and by States have been presented by considering TDAP Vaccine as 1+ HUMAN PAPILLOMAVIRUS SHOT. Based on the results, we can conclude that the confidence intervals for each state of the US are significant. 

Table 4 presented information about the sample sizes and 95% weighted confidence interval of each sample characteristics of adolescents aged 13-17 years in the United States in 2021.  Besides, vaccination coverage estimates amongst adolescents aged 13-17 years in the United States has been provided in Table 5 which includes unadjusted weighted vaccination coverage estimates for all the selected variables from model 1, model 2 and model 3 based on the vaccine type of “1+ HUMAN PAPILLOMAVIRUS SHOT”. According to the table 6, the type III test of effect for models using NIS-Teen 2021 for the vaccine type of “1+ HUMAN PAPILLOMAVIRUS SHOT” has been presented for model 2, 3 and 4. In model 2, Age (years), Sex of Adolescent, Race/Ethnicity, Mother's Educational Level, Mother's Marital Status, Income to Poverty Ratio, Medical Insurance, Well Child Visit at Age 11-12 Years, Census Region and Vaccination Facility Type are the variables that were significant. But, mother's age was not significant. In model 3, only Sex of Adolescent, Race/Ethnicity, Mother's Educational Level, Income to Poverty Ratio, Well Child Visit at Age 11-12 Years, Census Region and Vaccination Facility Type were significant. 

Based on the results of the Wald chi-squares test in model 3, the p value for the variables Sex of Adolescent, Race/Ethnicity, Mother's Educational Level, Income to Poverty Ratio, Well Child Visit at Age 11-12 Years, Census Region and Vaccination Facility Type are less than 0.05. So, we conclude that these variables have significant effect on this survey and these variables will remain in the model. Finally, as can be seen from the model 4 results, all the 7 variables in model 4 were significant. 

In this project, we have performed data analysis of the 2021 National Immunization Survey–Teen (NIS–Teen) on the total sample size which is equal to 18,002 to determine the coverage estimates of the vaccine 1+ HUMAN PAPILLOMAVIRUS SHOT. Descriptive statistics has been presented by providing graphs and report tables of weighted and unweighted percentages. Also, chi-square test statistics and confidence intervals have been presented to find significant variables. Moreover, we compared 4 different models based on the Wald Chi-Square test statistics to Indicate which variable or variables are associated with the selected type of vaccination which was 1+ HUMAN PAPILLOMAVIRUS SHOT and according to the final result, the best model has been presented. 








