# WeRateDogs-Twitter-Analysis
## by Yueh-Han Chen
## Context
Many people have their cute dogs and their dogs’ social accounts. However, most of them typically do not run their accounts very well due to lacking the knowledge of what the audience likes and what drives their favorite and retweet counts. Therefore, I wanna investigate these 3 questions:

> 1. Which stage of dogs got the highest retweet counts and favorite counts?
> 2. Whats are the top three breeds of dogs got the average highest retweet counts?
> 3. Whats are the top 5 underrated and overrated breeds of dogs? (being underrated means got the low scores from WeRateDogs but got high retweet counts and vice versa)?

## Main File Explanation:
- The main analysis file is wrangle_act.ipynb
- The final report is WeRateDogs_Analysis.pdf

### Before jumping to the analysis, we need to understand our limitation and whether other factor in WeRateDogs affect the favorite and retweet counts :

### limitation:

- Limitation 1: There are only 15% of the data have stages means the analysis about stages will will be 85% degree inaccurate.
- Limitation 2: There are 80% of the data have predicted breeds means the future prediction about breeds will be around 20% degree inaccurate.

**Other factor in WeRateDogs:**

- whether the ratings in WeRateDogs' posts affect the results?

From my analysis, I can tell that the ratings given by WeRateDogs' posts highly affected the results, which means the results can be manipulated by the content writer.

## 3 research questions

> 1. Which stage of dogs got the highest retweet counts and favorite counts?

Insight: The stage of Puppo got the highest retweet counts and favorite counts, which is almost 3 times higher than the breed of pupper.

> 2. Whats are the top three breeds of dogs got the average highest retweet counts?

I used 3 criteria to extract the result:

#1. the breeds that have at least 10 counts because the data is more stable
#2. which's std shoould be lower than 4446.856819 (std of whole dataset)
#3. which's mean is bigger that 4659.227536(mean of whole dataset).

Insight: Great Pyenees, Cardigan, and Golden retriever are top 3 highest average retweet counts by predicted breeds. And, the top 1 breed get average 600 counts higher than the top 2 one.

> 3. Whats are the top 5 underrated and overrated breeds of dogs? (being underrated means got the low scores from WeRateDogs but got high retweet counts and vice versa)?

Insight: 

The top 5 most frequently underrated breeds by WeRateDogs are Labrador Retriver, Golden Retriever, pug, Pembroke, maiamute. The top 1, Labrador Retriver is almost as 2 times frequently underrated as Pembroke.

The top 5 most frequently overrated breeds by WeRateDogs are Golden Retriever, Labrador Retriver, Rottweiler, Pomeranian, Chihuahua. The top 1, Golden Retriever, is almost as 2 times frequently overrated as Rottweiler.
