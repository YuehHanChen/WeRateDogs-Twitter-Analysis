# WeRateDogs-Twitter-Analysis

Many people have their cute dogs and their dogs’ social accounts. However, most of them typically do not run their accounts very well due to lacking the knowledge of what the audience likes and what drives their favorite and retweet counts. However, in this analysis, we analyze 3 questions :

> 1. Which stage of dogs got the highest retweet counts and favorite counts?

> 2. Whats are the top three breeds of dogs got the average highest retweet counts?

> 3. Whats are the top 5 underrated and overrated breeds of dogs? (being underrated means got the low scores from WeRateDogs but got high retweet counts and vice versa)?

### Before jumping to the analysis, we need to understand our limitation and whether other factor in WeRateDogs affect the favorite and retweet counts :

### limitation:

- Limitation 1: There are only 15% of the data have stages means the analysis about stages will will be 85% degree inaccurate.
- Limitation 2: There are 80% of the data have predicted breeds means the future prediction about breeds will be around 20% degree inaccurate.

**Other factor in WeRateDogs:**

- whether the ratings in WeRateDogs' posts affect the results?

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3f63e6a8-b3bc-471f-bde9-0f570cec99f4/_2020-04-08_1.28.34.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3f63e6a8-b3bc-471f-bde9-0f570cec99f4/_2020-04-08_1.28.34.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ef2f07ba-1449-4fc3-a36f-1765561dc532/_2020-04-08_1.28.42.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ef2f07ba-1449-4fc3-a36f-1765561dc532/_2020-04-08_1.28.42.png)

From this information, we can tell that the ratings given by WeRateDogs' posts highly affected the results, which means the results can be manipulated by the content writer.

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

Insight: 

The top 5 most frequently overrated breeds by WeRateDogs are Golden Retriever, Labrador Retriver, Rottweiler, Pomeranian, Chihuahua. The top 1, Golden Retriever, is almost as 2 times frequently overrated as Rottweiler.
