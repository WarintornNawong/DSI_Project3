# FAKE NEWS DETECTION IN PROJECT 3

# Problem Statement
To eliminate Fake News in Reddit Subreddit to avoid being posted by the malicious people to delude or take advantage of the fake news such as political or diplomatic activities.

## Why does ‘Fake News’ matters?

![image](https://user-images.githubusercontent.com/104628789/203228829-f7c972f1-daec-4ff9-ba22-d5edbe0d7b9e.png)


## Data Dictionary

The datasource is retrived from "Reddit API" with the following items,

1. **Fake News** : (r/fakenews, r/AteTheOnion, r/TheOnion)
2. **Real News** : (r/news, r/worldnews, r/UpliftingNews, r/Coronavirus)


| Data Columns | Description                |
| ------------ | -------------------------- |
| name         | name of the user           |
| title        | title of subreddit post    |
| text         | text within subreddit post |


The data is filtered in the contemporary topics i.e. President Joe Biden, Trump , Queen Elizabeht, War in Russia Ukrain etc. to ensure that the fake and real have the same issue within the same timeline for reddit

![image](https://user-images.githubusercontent.com/104628789/203228424-8889a59b-26b2-450d-99b3-8f5b4265d30a.png)


# Model Development Plan

1. Research and Data Exploring.
2. Data Gathering.
3. Scenario Analysis.
4. Model-Fine Tuning.
5. Performance & Reliability Test.
6. "Go Live"

# Final Dataset Stistics.

The proportion between “Fake News” and “Real News”.

![image](https://user-images.githubusercontent.com/104628789/195742861-e6a4e82e-b003-4d5e-8420-f2c5c782becc.png)

TOP Commons Words

![image](https://user-images.githubusercontent.com/104628789/195742919-16bfe675-266d-4274-831c-bdcc24aa2739.png)

# First Trial-Model



# Reliability improvement Journey

To improve model applicability, We established the reliability improvement journey to find the most reliability model for fake news detection.

![image](https://user-images.githubusercontent.com/104628789/203233887-28321d94-eff9-49d5-8eb1-362897121d18.png)




# Final Model Summary

After performing model as per timeline, the final model has been summarized in the following picture in two forms - **Predicted Model - Multinomial Naive Bayes  ** is the model whihc has been applied for fake news prediction and **Explained Model - Logistic Regression** is the model to deliver the coefficient for explaination purpose. 

![image](https://user-images.githubusercontent.com/104628789/203230503-d0202af1-4dc7-49f2-8a99-9121757e26f5.png)

## Way Forward

In order to address the weakness of model issue, I would like to propose the four main area for the further improvement.

![image](https://user-images.githubusercontent.com/104628789/203229709-f683fd8f-d94a-4973-8bec-d3d0755e91c8.png)














