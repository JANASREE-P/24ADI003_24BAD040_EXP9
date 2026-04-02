# 24ADI003_24BAD040_EXP9
SCENARIO 1:USER BASED COLLABORATIVE FILTERING
DATASET:https://www.kaggle.com/datasets/rajmehra03/movielens100k
This scenario focuses on recommending movies to a user by analyzing the preferences of other users with similar rating patterns. A User-Item matrix is created from the MovieLens dataset, and cosine similarity is used to measure how closely users are related based on their ratings. The system then identifies the top similar users and predicts ratings for unseen movies to generate personalized recommendations. This approach is useful for understanding user behavior, but it can face challenges such as sparse rating data and scalability for large datasets.

SCENARIO 2:ITEM BASED COLLABORATIVE FILTERING
DATASET:https://www.kaggle.com/datasets/rajmehra03/movielens100k
This scenario recommends items by finding movies or products that are similar to those a user has already liked. An Item-User matrix is constructed, and similarity between items is calculated using cosine similarity or Pearson correlation. Based on the user’s rating history, the system suggests items that are closely related to previously preferred ones. Item-based collaborative filtering is often more scalable and stable than user-based filtering because item relationships change less frequently over time. It is especially effective in identifying similar products and improving recommendation consistency.
