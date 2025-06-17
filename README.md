# Lead-Score-Case-Study
## Problem Statement:
X Education, an online learning company, provides professional courses to industry experts. Each day, numerous professionals visit the company's website through various marketing channels such as search engines and partner platforms. These visitors may explore courses, watch informational videos, or fill out a form with their contact details, thereby becoming leads. Additionally, leads are also generated through past referrals.

Once a lead is acquired, the sales team engages with them through calls and emails in an effort to convert them into paying customers. However, the current lead conversion rate is only 30%, meaning that out of every 100 leads, only about 30 successfully convert.

To enhance efficiency, X Education aims to identify high-potential leads ("Hot Leads"), those most likely to convert. By prioritizing these leads, the sales team can optimize their efforts, leading to a significant improvement in the overall conversion rate.

The lead conversion process follows a funnel approach, where a large number of leads enter at the top, but only a small fraction convert at the bottom. In order to improve conversions, potential leads need to be nurtured effectively through consistent communication and product education.

## Objective:
X Education has tasked you with building a predictive model using logistic regression to assign a lead score (ranging from 0 to 100) to each prospect. A higher score indicates a greater likelihood of conversion, allowing the company to prioritize high-value leads.

The CEO’s target is to increase the lead conversion rate to 80%, making it crucial for the model to be highly accurate and adaptable to evolving business needs.

## Dataset Overview:
You have been provided with a historical dataset containing approximately 9,000 data points, each representing a lead. The dataset includes various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, and more, which may influence the likelihood of conversion.

The target variable in the dataset is ‘Converted’, where:

1 indicates that the lead successfully converted into a paying customer.
0 indicates that the lead did not convert.
A detailed description of the dataset is available in the data dictionary provided in the zip folder.

Additionally, while working with categorical variables, you need to account for levels labeled as ‘Select’, as these represent unselected or missing values. Treating them appropriately is essential since they provide no meaningful information and could affect model performance.

## Goals of the Case Study: 
Develop a logistic regression model to assign a lead score (ranging from 0 to 100) to each lead, helping the company identify and prioritize potential conversions. A higher score indicates a hot lead with a strong likelihood of conversion, while a lower score suggests a cold lead that is less likely to convert.

Additionally, the model should be flexible enough to adapt to evolving business needs and address specific challenges outlined by the company. These challenges are detailed in a separate document, which should be completed based on the insights derived from the logistic regression model.

Finally, ensure that the findings, model performance, and strategic recommendations are effectively presented in the final PPT.

## Results Expected: 
A well-commented Jupyter note with at least the logistic regression model, the conversion predictions and evaluation metrics. The word document filled with solutions to all the problems. The overall approach of the analysis in a presentation Mention the problem statement and the analysis approach briefly Explain the results in business terms Include visualisations and summarise the most important results in the presentation A brief summary report in 500 words explaining how you proceeded with the assignment and the learnings that you gathered.
