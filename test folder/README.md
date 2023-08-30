2 Marks Answers:



1. **Goals of Recommender System:**
   - Personalization: Tailoring recommendations to individual users' preferences.
   - Increased Engagement: Keeping users engaged by suggesting relevant items.
   - Diversity: Introducing users to new and diverse items.
   - Serendipity: Recommending unexpected items that users might enjoy.
   - Improved Conversions: Increasing the likelihood of users making a purchase or taking desired actions.

2. **Different Models of Recommender System:**
   - Collaborative Filtering
   - Content-Based Filtering
   - Hybrid Approaches (Combining different models)
   - Matrix Factorization
   - Deep Learning-Based Models

3. **Different Types of Ratings in RS:**
   - Explicit Ratings: User provides direct feedback (e.g., star ratings).
   - Implicit Ratings: Derived from user behavior (e.g., clicks, views).
   - Binary Ratings: Indicates user's preference as binary (like/dislike).
   - Numeric Ratings: Use of numerical scales for preference.

4. **Different Types of Search Techniques in RS:**
   - Nearest Neighbor Search
   - Matrix Factorization
   - Clustering
   - Latent Semantic Analysis
   - Deep Learning Approaches

5. **Different Types of Filtering Techniques in RS:**
   - Content-Based Filtering
   - Collaborative Filtering
   - Hybrid Filtering
   - Demographic Filtering
   - Knowledge-Based Filtering

6. **Functions of RS:**
   - User Profiling
   - Item Profiling
   - Recommendation Generation
   - Evaluation and Testing
   - Feedback Incorporation

7. **Applications of RS:**
   - E-commerce product recommendations
   - Movie and music recommendations
   - News and content recommendations
   - Job or career suggestions
   - Social media content sorting

8. **Content-Based Filtering:**
   - Recommends items based on their inherent features and characteristics.
   - Focuses on understanding the user's preferences and suggesting items similar to what they have liked before.

9. **Advantages of Content-Based Filtering:**
   - Doesn't rely on other users' data.
   - Can provide personalized recommendations for new users.
   - Able to recommend niche items effectively.
   - Transparency in recommendations (explanation based on content features).
   - Can capture user's specific interests.

10. **Disadvantages of Content-Based Filtering:**
    - Limited diversity in recommendations.
    - Reliance on accurate item profiles and feature extraction.
    - Difficulty in understanding and incorporating user's changing preferences.
    - Can't suggest items outside the defined content space.

Sure, here's the continuation:

11. **Item Profile in Content-Based Filtering:**
    - It refers to a description or representation of an item's features and attributes.
    - These features could include metadata like genre, keywords, actors, and more.
    - The item profile helps the system understand the content of items and match them to user preferences.

12. **Preprocessing in Content-Based Filtering:**
    - Involves cleaning and transforming raw item data into a usable format.
    - This might include removing irrelevant information, standardizing text, and handling missing data.

13. **Feature Extraction in Content-Based Filtering:**
    - Process of selecting and transforming relevant attributes of an item into a feature vector.
    - Techniques include text analysis, image processing, and feature engineering to represent items quantitatively.

14. **Classification Algorithms in Content-Based Filtering:**
    - Decision Trees
    - Random Forest
    - Support Vector Machines
    - Naive Bayes
    - Neural Networks

15. **Explanation of Content-Based Filtering:**
    - Content-based filtering recommends items based on the user's past preferences and the inherent features of items they've shown interest in.
    - It creates profiles of both users and items, matching user profiles with item profiles.
    - Items similar to those previously liked by a user are suggested.
    - For example, if a user liked action movies in the past, the system might recommend new action movies.

16. **Advantages of Content-Based Filtering:**
    - No cold start problem (can recommend to new users).
    - Able to capture user's specific tastes.
    - Transparency in the recommendation process.
    - Can recommend niche or less popular items.
    - Doesn't require a large user base for effectiveness.

17. **Disadvantages of Content-Based Filtering:**
    - Limited discovery of new interests.
    - Reliance on accurate item profiles.
    - Difficulty in adapting to changing user preferences.
    - Can result in a filter bubble, limiting exposure to diverse content.

18. **Collaborative Filtering:**
    - Recommends items based on the collective behavior and preferences of a group of users.
    - Assumes that users who agreed in the past will agree again in the future.

19. **User-based Collaborative Filtering RS:**
    - Recommends items to a user based on preferences of similar users.
    - Requires a substantial user-item interaction matrix.
    - Neighbors' ratings are used to predict a user's preference.

20. **Item-based Collaborative Filtering RS:**
    - Recommends items based on their similarity to items the user has interacted with.
    - Generally more scalable than user-based approaches.
    - Utilizes item-item similarity metrics.

21. **Model-based Approaches in Collaborative Filtering RS:**
    - Matrix Factorization: Decomposing the user-item interaction matrix to find latent factors.
    - Latent Dirichlet Allocation (LDA): Incorporates textual information into collaborative filtering.
    - Neural Networks: Using deep learning architectures for collaborative filtering.

22. **Different Types of Attacks on Collaborative Filtering RS:**
    - Shilling Attacks: Injecting fake profiles or ratings to manipulate recommendations.
    - Profile Injection: Creating new user profiles to influence recommendations.
    - Profile Inference: Exploiting public data to infer user profiles.

23. **Model-based Collaborative Filtering:**
    - Utilizes machine learning models to predict user preferences.
    - Can incorporate various features and data sources.

24. **Matrix Factorization:**
    - A model-based collaborative filtering technique.
    - Decomposes the user-item interaction matrix into latent factors to predict missing values.

25. **Decision Tree in Collaborative Filtering RS:**
    - A classification or regression algorithm used for making decisions about a user's preferences based on certain attributes.
    - In collaborative filtering, decision trees can be used to partition users or items based on known preferences and make predictions for new cases.



5 Marks Questions





**26. What are the Goals of Recommender System?**

The goals of a Recommender System (RS) are as follows:

1. **Personalization:** RS aims to provide personalized recommendations to users, considering their preferences and behaviors, to enhance their experience and engagement.

2. **Increased Engagement:** By suggesting relevant and interesting items, RS seeks to keep users engaged and encourage them to explore more content.

3. **Diversity:** RS aims to introduce users to a diverse range of items to prevent the "filter bubble" effect and ensure exposure to various options.

4. **Serendipity:** Recommender systems try to surprise users with unexpected recommendations, promoting the discovery of items they might not have found otherwise.

5. **Improved Conversions:** RS helps increase conversion rates by suggesting items that users are more likely to purchase, thereby benefiting e-commerce platforms and other businesses.

**27. What are the different types of Ratings in RS?**

Recommender systems deal with various types of ratings:

1. **Explicit Ratings:** Users directly provide ratings (e.g., star ratings) indicating their preference for an item.

2. **Implicit Ratings:** Ratings inferred from user behavior, such as clicks, views, purchase history, and dwell time on items.

3. **Binary Ratings:** Users express a simple preference, like or dislike, without a numerical scale.

4. **Numeric Ratings:** Ratings that involve a numerical scale to measure the extent of preference.

**28. What are different types of Search techniques in RS?**

Recommender systems use various search techniques to find relevant items:

1. **Nearest Neighbor Search:** Finding items that are similar to ones the user has interacted with or liked in the past.

2. **Matrix Factorization:** Decomposing user-item interaction matrices into latent factors to capture hidden patterns.

3. **Clustering:** Grouping users or items based on shared characteristics to make recommendations within clusters.

4. **Latent Semantic Analysis:** Identifying latent semantic patterns in user-item interactions for better recommendations.

5. **Deep Learning Approaches:** Utilizing neural networks to learn complex patterns from user and item data.

**29. What are different types of Filtering techniques in RS?**

Recommender systems employ various filtering techniques:

1. **Content-Based Filtering:** Recommending items based on their features and user preferences.

2. **Collaborative Filtering:** Making recommendations based on the preferences of similar users or items.

3. **Hybrid Filtering:** Combining multiple techniques (e.g., content-based and collaborative) for more accurate recommendations.

4. **Demographic Filtering:** Using demographic data (age, gender) to make recommendations.

5. **Knowledge-Based Filtering:** Recommending items based on explicit knowledge about user preferences.




**30. What are the functions of RS?**

Recommender systems perform the following functions:

1. **User Profiling:** Creating user profiles by analyzing their behavior, preferences, and interactions.

2. **Item Profiling:** Building profiles of items based on their attributes and features.

3. **Recommendation Generation:** Using various algorithms to generate personalized recommendations for users.

4. **Evaluation and Testing:** Assessing the performance of recommendations through metrics like accuracy and user satisfaction.

5. **Feedback Incorporation:** Updating recommendations based on user feedback and interactions.

**31. What are the applications of RS?**

Recommender systems have diverse applications:

1. **E-commerce:** Suggesting products to customers for purchase.
2. **Media Streaming:** Recommending movies, music, and shows.
3. **News Platforms:** Personalized news article recommendations.
4. **Social Media:** Sorting and showing content on users' feeds.
5. **Travel:** Recommending destinations, accommodations, and activities.

**32. What are the Issues with RS?**

Recommender systems face challenges such as:

1. **Cold Start:** Difficulty recommending to new users or items with limited data.
2. **Data Sparsity:** Sparse user-item interaction data affecting accuracy.
3. **Diversity:** Tendency to recommend popular items, leading to reduced diversity.
4. **Privacy Concerns:** Gathering user data for recommendations raises privacy issues.
5. **Sudden Changes:** User preferences can shift abruptly, challenging adaptation.

**33. What is Feature Extraction in Content-Based Filtering? List some examples.**

Feature extraction involves transforming raw item data into meaningful features for content-based filtering. Examples include:

1. **Text Data:** Extracting keywords, topics, and sentiment from textual descriptions.
2. **Image Data:** Extracting visual features like color histograms, textures, and shapes.
3. **Audio Data:** Extracting features like tempo, pitch, and spectral characteristics.

**34. What is Nearest Neighbor Classification?**

Nearest Neighbor Classification is a technique where an item is classified based on the majority class of its nearest neighbors in a feature space. It's commonly used in collaborative filtering to find items similar to those the user has liked.

**35. What is Bayes Classifier?**

The Bayes Classifier uses Bayes' theorem to make predictions. It calculates the probability of an item belonging to a certain class given its features. In recommender systems, it can predict the likelihood of a user liking an item based on features.

**36. What is Rule-Based Classifier?**

A Rule-Based Classifier makes predictions using a set of if-then rules. In RS, this could involve rules like "If a user likes action movies and the movie is an action movie, recommend it."

**37. What are the advantages and disadvantages of Content-Based Filtering?**

**Advantages:**
- Independence from user data.
- Effective for new users or items.
- Can recommend niche or unique items.
- Provides transparent explanations for recommendations.
- Handles the cold start problem better than collaborative methods.

**Disadvantages:**
- Limited diversity in recommendations.
- Reliance on accurate item profiles.
- May not capture evolving user preferences.
- Tends to suggest similar items, hindering serendipity.
- Requires well-defined features for accurate recommendations.




**38. Explain Feature Extraction in Content-Based Filtering by giving two examples.**

Feature extraction involves transforming raw data into meaningful features for content-based filtering:

1. **Example - Movie Recommendations:**
   For movies, features could include genres (action, romance), actors, directors, and user reviews sentiment.

2. **Example - Music Recommendations:**
   For music, features could involve musical genres, tempo, instruments used, and lyrical themes.

**39. How do we obtain item features from Tags? Explain with a suitable example.**

Tags are user-generated labels describing item characteristics. To obtain item features from tags, one can create a binary feature vector indicating the presence or absence of each tag. For example, a movie might have tags like "action," "sci-fi," and "thriller." The binary vector would represent [1, 0, 1] indicating presence of action and thriller genres but absence of sci-fi.

**40. What is User-Based Collaborative Filtering RS? Explain with a suitable example.**

User-Based Collaborative Filtering RS suggests items to a user based on the preferences of users similar to them. For example, if User A and User B have liked similar movies in the past, the system recommends movies liked by User B to User A and vice versa.

**41. What is Item-Based Collaborative Filtering RS? Explain with a suitable example.**

Item-Based Collaborative Filtering RS recommends items based on the similarity between items. If Item X is similar to Item Y because many users who liked X also liked Y, then a user who liked Item X might be recommended Item Y.

**42. What is Regression Tree in Collaborative Filtering RS?**

A Regression Tree in Collaborative Filtering RS is a decision tree-based approach used for prediction. It can predict the rating a user might give to an item by partitioning the user-item space into segments and assigning ratings based on the majority rating in each segment.

**43. What is Rule-Based Collaborative Filtering RS?**

Rule-Based Collaborative Filtering RS uses predefined rules to make recommendations. For instance, a rule could state "If users have rated items A and B highly and they are similar to item C, recommend item C."

**44. What is Naive Bayes Collaborative Filtering RS?**

Naive Bayes Collaborative Filtering RS applies the Naive Bayes algorithm to predict user preferences. It calculates the probability that a user will like an item given the preferences of similar users.

**45. What is Singular Value Decomposition (SVD)?**

Singular Value Decomposition (SVD) is a matrix factorization technique used in collaborative filtering. It decomposes the user-item interaction matrix into three matrices, representing users, latent factors, and items. It helps discover latent features and patterns in the data.

**46. What is Collaborative Filtering RS?**

Collaborative Filtering RS predicts a user's preferences based on the preferences and behaviors of other users. It can be user-based (similar users) or item-based (similar items).

**47. What are different types of Attacks on Collaborative Filtering RS?**

1. **Shilling Attacks:** Malicious users create fake profiles or provide manipulated ratings to influence recommendations.
2. **Profile Injection Attacks:** Injecting fake user profiles to distort the collaborative filtering process.
3. **Data Poisoning Attacks:** Injecting false or biased ratings into the system to manipulate recommendations.
4. **Sybil Attacks:** Creating multiple fake user accounts to influence recommendations.
5. **Evasion Attacks:** Manipulating personal preferences to receive desired recommendations.














