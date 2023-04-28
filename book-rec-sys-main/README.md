# Book Recommendation System using Collaborative Filtering

# About

Recommendation system works on the principle of popularity or anything which is in trend. These systems check about the books which are in trend or are most popular among the users and directly recommend them.Different algorithms are used to create a recommender system that recommend books based on similarity and user rating. Since, here we are trying to recommend books to users based on their ratings the user gave , we are basically trying different models like Popularity based recommender system, Collaborative filtering based recommender system. The idea is to create recommender system that recommends books based on the user’s liking i.e. we recommends books based on the user’s rating. For this purpose we use recommender system of Collaborative Filtering system and Popularity based system to display top 50 books!

### 1.Data Cleaning and Pre-Processing
The dataset consists of three tables; Books, Users, and Ratings. Data from all three tables are cleaned and preprocessed separately.

### 2. Algorithms Implemented:

#### 2.1 Popularity Based Recommendation :

With its simplicity, this is the most basic recommendation system which offers generalized recommendation to every user based on their popularity.
This type of recommendation system makes generalized recommendation not personalized, meaning that this system will not take into account the personal preferences or choices, rather it would tell that this particular thing is liked by most of the users.To build one, the count of user ratings were taken for different books & the top 50 rated books are displayed on the home page.The criteria used to build popularity based system is considering only those books which have minimum 250 votes. 

#### 2.2 Collaborative Filtering Based Recommendation System.
We propose a method that estimates the final ratings with the help of collaborative filtering algorithm by finding the cosine similarity to recommend books. From cosine matrix we found the books similar to the book given by the user and recommended the top ‘n’ similar books.

#### Item-Item based filtering: 
In Item-Item based filtering, we explore the relationship between the pair of items (the user who read Y, also read Z). We find the missing rating with the help of the ratings given to the other items by the user.


#### User based filtering: 
User based filtering is a technique used to predict the items that a user might like on the basis of ratings given to that item by other users who have similar taste with that of a target user.if there is user A who has read and liked x  and y books, And user B has also liked this two books and now user A has read and liked some z book which is not read by B so we have to recommend z book to user B. 


### 3. Libraries Used:
- Pycharm IDE and Jupyter Notebook
- sklearn - Machine learning library
- numpy, scipy- number python library
- pandas - data handling library
- pickle, flask, gunicorn
