# **Background Problem**
---
At company ABC, the website has experienced a significant decrease in several key performance metrics, including a 20% decrease in Conversion Rate.
In an effort to understand the underlying causes of this decline, the marketing team has conducted a survey to gather feedback from users about their experience using the website.
Some of the responses from the survey indicate high levels of confusion and frustration, with users expressing that they feel confused and angry, leading them to ultimately exit the site. In response to these findings, the IT team has been tasked with creating a comparison between the old website and the new website to identify the best solution to address the existing issues. As the data team, our role is to assist in analyzing the data and providing insights to support the decision-making process in resolving this problem.

# **Objective**
---
- How many sample sizes are there for testing on the treatment website?
- Increasing the conversion rate metric to 25%
- What is the best website to use for marketing?

# **A/B Testing Website**
---
![Alt text](https://www.demltd.com/wp-content/uploads/2014/03/ab-testing1.jpg)

## **Simulation**

Can it be increased to 25% after treatment?
```python
# Mean conversion rate of the control group
conversion_rate_control = 0.635361

# Mean conversion rate of the treatment group
conversion_rate_treatment = 0.928945

# Calculate the percentage increase from the control group to the treatment group
increase_percentage = ((conversion_rate_treatment - conversion_rate_control) / conversion_rate_control) * 100

# Check if the increase is greater than 25%
if increase_percentage > 25:
    print(f"The difference of treatment compared to control is {increase_percentage:.2f}%. The increase in conversion rate exceeds 25%.")
else:
    print("The increase is less than or equal to 25%.")
```
**Answer the answer objective**
*   How many sample sizes are there for testing on the treatment website?
    - **Answer** : 33 size sample
*   Increasing the conversion rate metric to 25%
    - **Answer** : Yes, of course. After treatment, the conversion rate increased by more than 25%.
*   What is the best website to use for marketing?
    - **Answer** : Treatment website

## **Recommendation**
---
*What can we recommend for E-Commmerce?*

In launching a feature, it is not only considered from a statistically significant point of view, but also practically significant in business (e.g. cost).
