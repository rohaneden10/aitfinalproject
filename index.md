## Factors Affecting BMI and Factors BMI affects



### Introduction

Body Mass Index or BMI is a parameter which can be used to determenine whether a person is having appropriate weight for their height. Based on BMI, a person can be classified as Underweight, Healthy, Overweight or Obese. The article is about study of  the factors that affects  BMI and the factors  that BMI affects. In the study, the main focus was on to check whether there is any correlation between the smoking habits of a person and BMI and also to check how the insurance charges paid by the patient is affected by BMI and how the interaction of BMI and smoking habit afffect the insurance premium.

### Datasets Used
There were two datasets which were primarily used in the study with  BMI as the main variable of focus. The first dataset had many attributes of a subject like age, race, amount of nutrient intake etc. and the second dataset was about the insurance charges paid by the patients along with information about BMI and other factors as well. The dataset used was imported from kaggle website.


### Data Preprocessing
The datasets had a lot of variables of interests. The number of variables was narrowed down so as to focus on the topics of interest. The BMI quantitative value was categorized into different sections based on the values of BMI. They were Obese, Healthy, Underweight and Overweight. The columns with no values were dropped.This was done for the second dataset too.


## Visualizations
The below visualization show the count of records of people belonging to different BMI categories. The propotion of people who are obese and overweight is very high in the dataset compared to the people who are healthy and underweight.
![download (2)](https://user-images.githubusercontent.com/81614666/145688839-71b909fc-9d86-4d5e-ae40-3b79ac36ef90.png)

We tried to determine whether there is any relation between BMI and the insurance charges paid by the patient. A scatter plot was plot between the two values and fitted a regression line into the scatterplot.There was a slight increase in the insurance charges paid by the patient with increase in BMI indicated by the slope of the line.
![visualization (5)](https://user-images.githubusercontent.com/81614666/145688874-ce105ea5-5410-422d-bb44-99b0d8728109.png)


 To dig more into the case, we plotted another scatterplot using the same variables but used the BMI Category to group the data points. 
 ![download (3)](https://user-images.githubusercontent.com/81614666/145689225-30ef5c0e-6a0c-4c72-aca9-965628e7e095.png)
The below visualization filters the datapoints for obese category and plots a  scatterplot.The amount of charges paid by the people who were obese was very high when compared to others.
 ![download (4)](https://user-images.githubusercontent.com/81614666/145688904-cec2a4ef-3385-4821-ae75-367d7cee04eb.png)


 
 We tried to determine whether there is any relationship bewteen the combined effect of smoking and bmi on the insuracne charges. We plotted a sactter plot with bmi and charges and grouped the data points by smoking status. We also fitted regression lines to the same plot.
![download (6)](https://user-images.githubusercontent.com/81614666/145688936-799d6212-0768-4415-a037-5ff8192ded19.png)


 The  rate amount of charges paid by the subjects who are non smokers with increasing bmi was very less compared to the charges by people who are smokers. The rate of increase was almost exponential for the smokers.

![visualization (7)](https://user-images.githubusercontent.com/81614666/145688963-98720fe2-5195-438d-bf93-bf81b153a6a2.png)
![visualization (3)](https://user-images.githubusercontent.com/81614666/145689002-eac0ae70-92c5-4238-8768-91b5c2053b9b.png)
![visualization (7)](https://user-images.githubusercontent.com/81614666/145689027-1a66be08-8b44-4220-ab77-b576d4bac65d.png)


 







```markdown
Syntax highlighted code block![Uploading visualization (7).png…]()

# Data Preprocessing
The datasets had a lot of variables of interests. The number of variables was narrowed down so as to focus on the topics of interest. The BMI quantitative values was categorized into different sections based on the values of BMI. They were Obese, Healthy, Underweight and Overweight. The columns with no values were dropped.
## Header 2![visualization (1)](https://user-images.githubusercontent.com/81614666/145682609-5348be3a-b8a5-4070-87b8-eb69bc3f8fc8.png)

### Header 3
```markdown
Syntax highlighted code block

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](aitproject imagese/visualization (1).png))
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rohaneden10/aitfinalproject/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
