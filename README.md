# 💪Different Types of Recommendation Systems :
It is likely that you will concur that there are multiple approaches to determining what to suggest or recommend when a friend seeks our opinion. This principle is equally applicable to artificial intelligence.

thier are three techniques for constructing recommendation engines are
1. Simple Recommendation.
2. Content-based filtering.
3. Collaborative filtering.

## 1- Simple Recommendation
Recommend an item based on its own popularity,
Build Simple Recommender System based on the metric below:
```
weightedRating(WR) = ((v/v+m).R) + ((m/v+m).C)
```
## 2- content-based filtering:
This method generates suggestions *based on items* you have previously liked. It uses historical data such as purchase records and search history to identify similar products. 

> For example, if you rated the movie "Inception" with five stars, the system will recommend similar movies such as "Interstellar".

![download (2)](https://github.com/user-attachments/assets/e0f8c86e-eeb4-490c-a501-2eccd515dbb5)


However, if all recommendation systems solely relied on your viewing history, discovering new genres and films would be challenging. This is where **Collaborative filtering** comes into play. But what exactly does it entail?.


## 2- Collaborative filtering:
This method identifies other users who have similar preferences to you, and recommends items **based on their choices**. 

> For example, if you and your friend both like the movie "The Shawshank Redemption", and your friend also likes "Forrest Gump", the system will recommend "Forrest Gump" to you.

![download (3)](https://github.com/user-attachments/assets/1e203df6-0194-4d77-82dd-c5ea744ce66f)


## Dataset :
- The Movies Dataset : https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
- MovieLens dataset
'
  ```
   !wget http://files.grouplens.org/datasets/movielens/ml-latest-small.zip
   !unzip ml-latest-small.zip 
  ```


