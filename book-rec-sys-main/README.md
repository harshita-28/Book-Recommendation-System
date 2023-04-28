
# AVM Book Recommender

## Presentation
[Youtube link](https://www.youtube.com/watch?v=rdklwA2dxyI)

## Description
A Book Recommendation System which recommends the users a selection of books based on their interests.

Data used for this project was taken from [here](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

### 1.Data Cleaning and Pre-Processing
The dataset consists of three tables; Books, Users, and Ratings. Data from all three tables are cleaned and preprocessed separately as defined below briefly:

![Screenshot (1279)](https://user-images.githubusercontent.com/102828957/170858262-ae32a14a-5220-4b1d-b822-abd41ad90721.png)

### 2. Algorithms Implemented:

#### 2.1 Popularity Based Recommendation :

With its simplicity, this is the most basic recommendation system which offers generalized recommendation to every user based on their popularity. In a bookstore, if a certain book is popular among its customers & is also critically acclaimed, in the scenario that a new customer walks in & asks for the best, they would be suggested to try that book too. The same is true for movies, shows, music, etc. Whatever is more popular among the general public, is more likely to be recommended to new customers too.

This type of recommendation system makes generalized recommendation not personalized, meaning that this system will not take into account the personal preferences or choices, rather it would tell that this particular thing is liked by most of the users.

To build one, the count of user ratings were taken for different books & the top rated books are displayed below:

![Screenshot (1280)](https://user-images.githubusercontent.com/102828957/170858474-5246812e-19ff-4c9f-9849-c0e6fffd3f0c.png)



#### 2.2 Collaborative Filtering Based Recommendation System.
In Collaborative Filtering, we tend to find similar users and recommend what similar users like. In this type of recommendation system, we don’t use the features of the item to recommend it, rather we classify the users into the clusters of similar types, and recommend each user according to the preference of its cluster.

![Screenshot (1281)](https://user-images.githubusercontent.com/102828957/170858659-f9298ed1-5e6d-4a81-924a-c89e6d3e2776.png)

### 3. Libraries Used:
- ipython-notebook - Python Text Editor
- sklearn - Machine learning library
- numpy, scipy- number python library
- pandas - data handling library
- pickle, flask, gunicorn
## How to run?
- Clone (Download) it on your computer

- Go to the project directory

- Extract the zip file and open it with editor.

- Install pythonn and editor

- install the packages writte in requirement.txt

```bash
  pip install package_name
```

- Run the code pf `app.py` file

- Click on the link which will appear in terminal

- Enjoy!


## UI 
![Screenshot (1282)](https://user-images.githubusercontent.com/102828957/170859732-4ea03888-3b6d-44f6-b54f-d68546932f2d.png)

![Screenshot (1283)](https://user-images.githubusercontent.com/102828957/170859739-ffecabd4-4096-451c-bde7-2ad90eb3b353.png)

![Screenshot (1284)](https://user-images.githubusercontent.com/102828957/170859760-ff191188-1497-4f9a-9c8a-8ea9c77fac28.png)

![Screenshot (1285)](https://user-images.githubusercontent.com/102828957/170859820-d932b364-4282-4fbb-94ec-50b82f21b1fe.png)

![Screenshot (1286)](https://user-images.githubusercontent.com/102828957/170859769-bc8162f3-c7ad-4807-a911-434034a16534.png)

![Screenshot (1287)](https://user-images.githubusercontent.com/102828957/170859843-2e748572-2ac8-4dff-825e-4567d9c2e75e.png)

![Screenshot (1288)](https://user-images.githubusercontent.com/102828957/170859848-7b6626ef-abc4-4ba1-8aef-1ea785bd8fdb.png)

![Screenshot (1289)](https://user-images.githubusercontent.com/102828957/170859872-3267b64c-2787-4165-8055-dedb39fdb30c.png)

![Screenshot (1290)](https://user-images.githubusercontent.com/102828957/170859907-736b6a64-fa01-4637-86eb-3b0e4d84f72c.png)

![Screenshot (1291)](https://user-images.githubusercontent.com/102828957/170859877-2d1c7ebc-5927-4317-afcc-ae4944363457.png)

![Screenshot (1292)](https://user-images.githubusercontent.com/102828957/170859880-47e3114a-cdf5-45ab-aef5-1a79a26b1a77.png)

## Documentation
[link](https://docs.google.com/document/d/1I6EbrpVH3AzW8tz2JYAEUYAsufXCpcyR6dckr4Ig3_0/edit)
