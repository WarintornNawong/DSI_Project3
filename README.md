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

Confusion Matrix

![image](https://user-images.githubusercontent.com/104628789/195743039-5c951a41-1dd3-4d0d-9a2b-9827378c5665.png)

Logistic Regression Coefficients

![image](https://user-images.githubusercontent.com/104628789/195743088-4516de17-10c2-44da-8b1b-3a1620cb71e2.png)


# Final Model Summary

Confusion Matrix

![image](https://user-images.githubusercontent.com/104628789/195743272-db054e2a-9e18-474b-be9c-a5f29f9d0b42.png)

Best Parameter

Max Features : 1000 
Min DF : 1
N-Gram Analysis : (1,1)

![image](https://user-images.githubusercontent.com/104628789/195743352-c94c7ff8-d814-48be-8eca-849e4dac9834.png)













