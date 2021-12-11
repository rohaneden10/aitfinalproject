## Factors Affecting BMI and Factors BMI affects



### Introduction

Body Mass Index or BMI is a parameter which can be used to determine whether a person is having appropriate weight for their height. Based on BMI, a person can be classified as Underweight, Healthy, Overweight or Obese. The article is about study of  the factors that affects  BMI and the factors  that BMI affects. The goal of our project is to find the major factors that affect the BMI directly and indirectly. We all for a reason know that BMI is mainly dependent on the day-to-day caloric intake and the physical activity that a person does every day. But we wanted to go a little deep and analyse what are the other factors that could affect the BMI. For example, the person’s race, parity, and other demographics.

![bmi-body-mass-index-formula-260nw-765689137](https://user-images.githubusercontent.com/81614666/145690469-af9afed6-2202-425d-b524-db11651a3261.jpg)

After doing this we also wanted to know how much of an impact does BMI and other health related markers play a role in the insurance charges that a person must pay annually. Of course, we all know that BMI must be having a significant impact on this factor but we wanted to compare this with other health markers.



### Datasets Used
There were two datasets which were primarily used in the study with  BMI as the main variable of focus. The first dataset that we used was Piyathilake diet dataset.The population that this study analyzed were pregnant women whose age ranged from 20-40 and most of them have had kids before. The reason why we chose this was we had a lot of variables to play like the nutrition, physical activity, type of food that they had with serving sizes were provided in the dataset. We wanted to find what are the major factors that affect the BMI.
The second dataset that we used consists of age, BMI, smoking status and the insurance charges that the person will pay at the end of the year.The datasets were imported grom kaggle.



### Data Preprocessing
The datasets had a lot of variables of interests. The number of variables was narrowed down so as to focus on the topics of interest. The BMI quantitative value was categorized into different sections based on the values of BMI. They were Obese, Healthy, Underweight and Overweight. The columns with no values were dropped.This was done for the second dataset as well..


## Visualizations
The below visualization show the count of records of people belonging to different BMI categories. The propotion of people who are obese and overweight is very high in the dataset compared to the people who are healthy and underweight.
![download (2)](https://user-images.githubusercontent.com/81614666/145688839-71b909fc-9d86-4d5e-ae40-3b79ac36ef90.png)

We tried to determine whether there is any relation between BMI and the insurance charges paid by the patient. A scatter plot was plot below between the two values and fitted a regression line into the scatterplot.There was a slight increase in the insurance charges paid by the patient with increase in BMI indicated by the slope of the line below.
![visualization (5)](https://user-images.githubusercontent.com/81614666/145688874-ce105ea5-5410-422d-bb44-99b0d8728109.png)


 To dig more into the case, we plotted another scatterplot below using the same variables but used the BMI Category to group the data points. 
 
 ![download (3)](https://user-images.githubusercontent.com/81614666/145689225-30ef5c0e-6a0c-4c72-aca9-965628e7e095.png)
 
The below visualization filters the datapoints for obese category and plots a scatterplot.The amount of charges paid by the people who were obese was very high when compared to others.We can see that in the cluster on the top of above visualization. 

 ![download (4)](https://user-images.githubusercontent.com/81614666/145688904-cec2a4ef-3385-4821-ae75-367d7cee04eb.png)
 
 We first decided to go with linear regression but the result was not significant. But when we grouped by the BMI we could clearly find the cluster of obese people paying high insurance charges.


 
 We tried to determine whether there is any relationship between the combined effect of smoking and bmi on the insuracne charges. We plotted a sactter plot with bmi and charges and grouped the data points by smoking status. We also fitted regression lines to the same plot.
![download (6)](https://user-images.githubusercontent.com/81614666/145688936-799d6212-0768-4415-a037-5ff8192ded19.png)


 The  rate of amount of charges paid by the subjects who are non smokers with increasing bmi was very less compared to the charges by people who are smokers. The rate of increase was almost exponential for the smokers.From the linear regression we can conclude that smoking+obesity has a direct impact on the amount of charges that you pay. You may get away by just being obese but smoking+obesity looks like a recipe for disaster.
 
 ![download (7)](https://user-images.githubusercontent.com/81614666/145690714-31ddc9fd-f5e4-4243-9695-27d6a3137cde.png)
 
 We all for a reason know that aged people are prone to paying more insurance compared to the young ones. So, we decided to see what age has to do with insurance charges in this case. We used the same plot but this time we grouped the people by their age. Surprisingly we found that even if you are aged you can get away by paying less charges if you can maintain your BMI lower than 30. 

 



![visualization (3)](https://user-images.githubusercontent.com/81614666/145689002-eac0ae70-92c5-4238-8768-91b5c2053b9b.png)
 
 We aslo tried to understand the relation between BMI Category and the races that we have available. The stacked bar graph above plots propotion of people in the different  BMI categories belonging To different races. The propotion of obese and overweight people in the African American race was very high compared to the Caucasian American race.
 
 ![visualization (4)](https://user-images.githubusercontent.com/81614666/145689558-2d14499f-5c35-48bd-9ade-2ed8cadc0122.png)
 
 We made a barplot to understand why the propotion of obese people was higher for African Amercian people. The barplot is plotted for race against the moderate_physical activity column and was able to find out that the amount of physical activity for African American people were lower, whcih would explain the situation of the race having higher number of Obese and overweight people.
 
 
# Conclusion
So we can conclude that obese people and people who smoke at the same time pay significantly higher charges. The above findings are limited to the scope of dataset and doesnt always mean that it will be true for the real world. 
 




 







