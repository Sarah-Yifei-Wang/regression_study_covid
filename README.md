# regression_study_covid
During the time of COVID-19, many studies have been conducted to assess the widespread use of face masks in reducing the spread of the disease. This is particularly true for when masks are used universally within communities with denser populations. The CDC has advocated for masks, or any cloth face coverings for that matter, as a barrier to prevent respiratory droplets from traveling into the air when a person coughs, sneezes, talks, or raises their voice. CNN reports that if 95% of Americans wore face masks in public, it could prevent more than 450,000 deaths by November 1, 2020. Despite the effectiveness of preventing spread of COVID-19 when wearing a mask, many have not followed suit in the accordance with CDC guidelines. As states enter different phases of reopening, many have executed mandatory face mask use policy for employees in public-facing businesses. The concept that this specific study will measure is

The effects of the policy of mandating face mask in public facing businesses on the total number of COVID cases recorded for each state.
We assume the dates on which the mandate was placed is critical to our study for measuring how the timeliness of the mandate date ultimately save thousands of lives. We also want to understand how other factors such the population at risk of serious illness, stay at home duration, business closed duration has played a role in the total number of cases and how they interact with face mask mandate policy.

In our study, we conducted various tasks prior to our linear regression models:

1. First, we studied the data and tried to understand the distribution of total number of cases by each state, which we used as dependent variable for our study. Our aim in understanding the distribution is to identify outliers as well as get a general idea about the dependent variable spread.
2. Then we cleaned our data and identified issues such as duplicates or missing value that can affect our study.
3. We also performed exploratory data analysis (EDA) in order to form our base model and identified key variables to be used for our linear regression models.
4. We identified required data transformation for effective study and required key variables created from 'Mandate face mask in public facing business' date
5. Furthermore, we also took into consideration the number of days businesses were closed, as the mandate only restricts employess in public-facing businesses; number of days stay at home policy was in place; population at risk and number of days the face mask mandate is in place.
6. We studied the correlation between the independent variables and with the dependent variable to assess our assumption.
7. We created base model and conducted 2 improvements on it. We checked the quality of model along with multicollinearity check.
8. Lastly, we assessed CLM assumptions and verified if any voilation are there. We also summarized statitical and practical significance of our study.
We did the study on ommitted variables before concluding.
