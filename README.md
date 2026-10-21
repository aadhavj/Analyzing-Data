# Analyzing Data

The following project was made to complete the Sunset High School Artificial Intelligence assignment, analyzing data. Note to grader, the **matplotlib** graphs are present at the bottom of the printed data in the Juypter notebook file.

___

## Multi-variable linear regression model

The created linear regression model analyzes factors such as **Duration_Watched (minutes)**, **Genre**, **Age**, **Gender**, **Subscription_Status**, and **Languages** to predict the target variable: **ratings**.
___

## Model accuracy

Despite the low root mean squared error presented by the model, it was terrible at predicting the actual rating values (Tends to predict around 3 for all cases).

> MSE training data: 1.9660063707317872
> MSE testing data: 1.9732500366916386

## Questions to answer from model?

Before creating the mode, I had a few questions that I wanted to answer using it.

First, **Do any of my target variables have a significant impact on the ratings from streaming services?**

Answer: No, the variables don't seem to have any impact on predicing the ratings, an observation I made after seeing the low correlation from the Matplotlibs between the numerical variables and the target variable.

Second, **Do really short movies recieve bad ratings?**

Answer: No. According to the graphs from the matplotlibs, it seems that there is no correlation between movie duration and ratings.

<img width="386" height="263" alt="image" src="https://github.com/user-attachments/assets/a9fd9194-618b-4c13-903e-4b0eef743069" />

Finally, **Does a user's age have a visible effect on the ratings they give?**

Answer: No. The graph shows that there is a 0.008 correlation coefficient, meaning that there seems to be no correlation between the variables.

<img width="386" height="262" alt="image" src="https://github.com/user-attachments/assets/f6c617fa-cee6-42fb-95d3-5e7ce6e07d4e" />

___
