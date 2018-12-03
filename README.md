# Udacity_DataAnalyst
 This is a project work I did for the **Udacity Data Analyst Nanodegree**
 
 ## Project 1 - Global Weather Trends 
 In this project, I have analysed local and global temperature data and compared the temperature trends with where I live to overall global   temperatures
 
 * Extract the data from the database.
 * Created a line chart that compares my city’s temperatures with the global temperatures. I made sure to plot the moving average rather    than the yearly averages in order to smooth out the lines, making trends more observable
 * Made observations about the similarities and differences between the world averages and your city’s averages, as well as overall trends.
 
### My Inferences
 
a) Global temperatures are very less compared to Hyderabad and Delhi

b) The temperatures for all the 3 categories have increased marginally in the last 200 years of data

c) The lowest temperatures found for Global (7.3 deg C) around 1820, whereas for Hyderabad (25.8 deg C) around 1830. and for Delhi (26 deg Celcius) around 1820

d) Hyderabad temperature increment is more at present compared to Global and Delhi

e) Exactly 50 years from the year 1807, we observe that Global and Delhi have their temperatures dipped but for Hyderabad it is consistent.

f) The global temperature remained consistent until the year 1957, but after 1957 increased.
there seems to be a lot of change in temperatures . Hence global temperatures are 

g) At every 50 years interval, the temperatures are shown in chart , Hence we can observe that temperatures have changed by +/ -0.3

h) The correlation coefficient for (Global vs Delhi -> 0.937) and (Global vs Hyderabad -> 0.687) So from above, the changes in Global temperature will have huge impact to Delhi when compared to Hyderabad

i) The difference in 12 year MA temperatures for Global (0.89) , Hyderabad(1.16), Delhi (1.04)
(comparison done w.r.t 1807 vs 2013)
 

 
 ## Project 2 - No Show Appointments

This project is based on the dataset which collects information from 100k medical appointments in Brazil and is focused on the question
of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

● ‘ScheduledDay’ tells us on
what day the patient set up their
appointment.

● ‘Neighborhood’ indicates the
location of the hospital.

● ‘Scholarship’ indicates
whether or not the patient is
enrolled in Brasilian welfare
program Bolsa Família.

● Be careful about the encoding
of the last column: it says ‘No’ if
the patient showed up to their
appointment, and ‘Yes’ if they
did not show up.


### Business Questions I tried to answer

1. Is there any Gender difference in having a patient to be with status Show / No-Show? 

2. Is there any Age difference in having a patient to be with status Show / No- Show?

3. Is there any Age difference along with Gender difference with the status of Show / NoShow?

4. On which weekday/day/month maximum appointments are getting finalized with Show status?

5. Is there any specific medical condition that is driving the patient(Male/Female) to go to for the doctor appointment?

6. Are the digital /social media reminders are helping the patients to take doctor's appointment?

7. Is Scholarship from the government helping patients for good turnaround for physician visits?

8. Which neighbourhood regions are actually have higher appointments with physicians?

9. What factors are important for us to know in order to predict if a patient will show up for their sceduled time?

### Inferences

* Of those patients who have showed up for appointment, majority patients with age group from 20 to 40 did not show up for the appointment when compared to age groups 0-20, 40-60 and 60 plus. of these 20 to 40 age group, Female patients are NOT active in getting appointment with doctors when compared to similar age group of Males

* Majority of the visits or appointments happend on the weeekdays (Monday, Tuesday and Wednesday) when compared to weekends. Hence weekdays are the best for good conversion for appointment

* Hypertension and Diabetes patients are attending the doctor when compared to other medications. Age ranges from 40 to 80 - with females conversion is better than Males.

* Alcoholism patients from Male group have showed up for physician visit when compared to female and they are in range from 45 to 65.

* If there are any promotions towards digital media either through SMS / emails, the conversion for physician visit will improve and from the data it is inferred that patients (~25K visits) who have recieved SMS have turned up for physician visit.

* On contrary actually we would expect that patients who have got scholarship should have been all attended the physician but it seems that ~25% of patients did not attend.

* Majority of the visits happend from Jardim Camburi, but we are not sure on why this happend. There might be many reasons like majority of the patient population might be from that place or majority of the physicians are from that location. This is one of the limitations


## Project 3 - Analyze_A_B Test Analysis

A/B tests are very commonly performed by data analysts and data scientists. It is important that we get some practice working with the difficulties of these

For this project, I have worked to understand the results of an A/B test run by an e-commerce website. My goal was to work through this  to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


### Inferences

* The probability of an individual converting regardless of the page they receive is 11.96%

* Given that an individual was in the control group, the probability they converted is 12.04%

* Given that an individual was in the treatment group, the probability they converted is 11.88%.

* The probablity users converted in both control and treatment group are almost close or similar to each other and probability of an individual converting regardless of the page they receive. therefore, **there is no evidence that new page leads to more conversions**

#### Interpretations from the Logistic Regression / Logit Model

* From the above Logit Regression Results, we can see that the only intercept's p-value is less than 0.05, which is statistically significant enough for converted rate but other variables are not statistically significant.

* The country a user lives is not statistically significant on the converted rate considering the page the user land in.

* For every unit for new_page decreases, the user getting converted will be 7.0% more likely to happen while holding all other varibles constant.

* The user getting Converted is 1.08 times more likely to happen for UK and new page users than CA and new page users while holding all other varible constant.

* The user getting Converted is 1.04 times more likely to happen for US and new page users than CA and new page users while holding all other varible constant.


