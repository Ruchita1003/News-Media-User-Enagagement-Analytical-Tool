# News-Media-User-Enagagement-Analytical-Tool

<!-- Click here for the Video Walkthrough: [![Video Walkthrough](https://img.shields.io/badge/-Analyzing%20OTT%20Platforms-red??style=social&logo=Youtube&link=https://www.youtube.com/watch?v=XDs-nJZxyO4/view?usp=sharing)](https://www.youtube.com/watch?v=XDs-nJZxyO4/view?usp=sharing) -->

Notebook best viewed in Google Collab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ruchita1003/News-Media-User-Enagagement-Analytical-Tool/blob/main/Project_Final.ipynb)<br>

### Steps to run the project:
- Open the notebook in colab.
- Add the articles.csv to the data folder inside the colab.
- Select 'Run All' to run the entire notebook at once.

_______________________________________________________________________________________________________________________________________________________________________

## **Problem Domain**:

### The primary domain that we identify here is ***Media Analytics***. To narrow it down further, we are concentrating more on ***user engagement***  of the news wing of media.


### 1. Unveiling Reader Engagement Behaviour using Supervised Learning:

- We want to be able to predict whether an article will feature as a "Top Article" or not. It is vital for any publication agency to understand the reach of any article in the pipline. This assists the publication house in strategic allocation of their resources among all the articles in the pipline.                  

- Our project also aims at predicting the "Popularity Score" and the "Enagagement Count" of an article. The goal underneath this is to be able to understand and foretell users/readers engagement behaviour with the article. We wish to speculate the number of likes, shares, comments and reactions on a article before it is released as these are some of the primary popularity/engagement driving parameters. Our model will be able to help an author/publication get insights for a particular article which "headline" or what "content" will garner the most enagagement.

- We are also keen on exploring whether we can let agencies know which release time is the best for maximum user engagement. For example, BBC News would love to know what is the best time of the day for them to release an article belonging to Sports domain in order to maximize user enagegement.



---


### 2. Understanding the influence of certain keywords on an article's popularity using Unsupervised Learning:
- Our team is also inclined towards performing topic modeling to understand the underlying topic pool of all articles. This will help us categorize articles to domains they belong to. For example Politics, Crime, Hollywood, Sports etc. (Currently our dataset does not contain this). If possible we would like to extend our idea into understanding which keywords have a strong positive effect on the article's popularity/engagement. A practical use case of this could be as follows ~ we will help The New Yorker know usage of which keywords in a sports article will most likely boost reader engagement.
      

---


### 3. Analyze if an article is polarizing
- If the article is polarizing and has been receiving a lot of engagement, this article and the author gets flagged. The agency and Government can then monitor these authors to ensure they are not trigerring riots and other public disturbances
- We can see that Polarizing content garners a lot of views, which is problematic
- https://journalism.csis.org/thinking-outside-the-bubble-addressing-polarization-and-disinformation-on-social-media/
- https://www.brookings.edu/blog/techtank/2021/09/27/how-tech-platforms-fuel-u-s-political-polarization-and-what-government-can-do-about-it/
- https://sites.bu.edu/pardeeatlas/back2school/how-the-american-media-landscape-is-polarizing-the-country/

_______________________________________________________________________________________________________________________________________________________________________

## **Dataset**:

 - For the data set used a Kaggle Data set which had the details of different articles and how the users engaged with it.
 - Link : https://www.kaggle.com/datasets/szymonjanowski/internet-articles-data-with-users-engagement
 - It has 15 columns and 10437 Rows

_______________________________________________________________________________________________________________________________________________________________________

## **Insights**:

### Top articles
- We found that only 12% of the total articles were Top Articles

### Best Release time for articles
- We found that the best release time for articles are during the Afternoon
- From 14:00 - 17:00

### We can see that the emotion for most top articles are neutral
- But Negative is still higher than Positive.
- Thus Negative articles might have a higher propensity to be a top article

_______________________________________________________________________________________________________________________________________________________________________

## **Outcomes:**

### 1) We are able to predict the popularity score for a given title and how much engagement it might receive.

- Knowing if an article has the potential to be a "top article" can be helpful for media houses because it can inform their decision-making and help them prioritize certain content. For example, if a media house knows that a particular article is likely to generate a lot of traffic and engagement, they may choose to promote it more heavily or allocate more resources to its production. This can help the media house attract more readers and potentially increase revenue from advertising or subscriptions.

- Additionally, knowing if an article has the potential to be a top article can help media houses gauge the public interest in a particular topic. If an article is likely to be popular, it may indicate that there is a high level of interest in the topic among the general public. This information can be useful for media houses as they plan their editorial content and decide what topics to cover in the future.

- Finally, knowing if an article has the potential to be a top article can also help media houses assess the quality of their content. If an article is likely to be popular, it may indicate that it is well-written, informative, and engaging. This can help media houses evaluate their editorial processes and make improvements where necessary to ensure that they are producing high-quality content that resonates with their readers.

### 2) We saw that model that we selected found the below items to be important while classiying an article as top or not
- If the topic was Negative or not
- The content length 
- Engagment that the article garners

Content Length
- Thus maybe top articles could be articles which are not too long and hold the readers attention.
- Thus publishers could see what content length suits in garnering engagment for them.

### 3) Polarity Flagger

- One reason why polarizing content is so effective is because it taps into our emotions. When we see something that makes us angry or afraid, our brains are more likely to pay attention to it and remember it. This is why polarizing content often goes viral - people are more likely to share it with others if they have a strong emotional reaction to it.
- In conclusion, polarizing content is spreading because it is effective at capturing our attention and reinforcing our beliefs. While it can be useful for generating debate and discussion, it can also be dangerous because it can create division and conflict. It is important for people to be aware of the effects of polarizing content and to approach it with caution.

_______________________________________________________________________________________________________________________________________________________________________

## Conclusion:

### **This tool is primarily targetted for news article publication houses who can benefit by using it before publishing an article**<br>
**By predicting the popularity score of an article:**<br>
The Publication house can understand if an articles has the propensity to garner high engagement and views from the users and readers <br>
**By predicting if an article will be top or not:**<br>
We can see if the Article make it to the top and has a chance of being the top article. <br>
**By predicting if an article will be polarizing or not:**<br>
After we have provided all of these tools to Publishing houses to increases their engagement we also wanted to provide <br>
them with a check that can help to stop the spread of content that can be polarizing
_______________________________________________________________________________________________________________________________________________________________________
