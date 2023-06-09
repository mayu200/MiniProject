# MiniProject

**Movie recommendation system using content based filtering**

**Introduction**

Now days Recommendation system is playing a vital role in YouTube, Netflix, amazon prime, 
Instagram and Facebook etc., where system recommend an item to the user based on the ratings or 
preferences given to an item, the system predicts the ratings or preferences given to an item and 
recommend an item to user.
In this project we used content-based filtering technique and we taken the dataset from the TMDB 
5000 movies dataset to build the model is the famous dataset and used streamlit for website 
development along with we also used some python libraries such as pickle, sklearn, NumPy, pandas, 
requests and AST. The main idea of this project is to build a model which helps the user in easy 
recommendation of movies by the system based on their behavior.

**Keyword:  Content-based Filtering, Stream lit, Sklearn, Pickle, Pandas, 
NumPy, Cosine distance, Bag of Words, AST, Count Vectorizer, Cosine Similarity.**

**Content-Based Filtering**

Content-based filtering methods are done based on user Characteristics. This method is used in 
situations where data is known on an item such as name, Location, or description and not on the user. 
It predicts the items based on user’s information and Completely ignores contributions from other 
users as with the case of collaborative techniques. It Uses the data that is provided by the user either 
explicitly or implicitly. When the user provides More content-based filtering mechanisms actions on 
the recommendations such as content-based Recommender the engine becomes more and more 
accurate.
Content-Based recommendation works on the principle that if a user likes a certain item then we 
recommend the user a similar item based on the item’s features or attributes. So in our case, if a user 
likes a movie of a particular genre or an actor then we recommend a movie on similar lines to our 
user. So, if a user has watched the movie Joker then our recommendation system would predict 
movies similar to Joker or with the same cast as that of Joker if we consider the movie’s cast.

**ALGORITHMS**

Some of the algorithms used in movie recommendation are COUNT VECTORIZER AND COSINE 
SIMILARITY.

**METHODOLOGY**

**1. Requirement/Data Gathering:**

Data is the most important and foundation for machine learning projects. Gathering data from various 
datasets is key for a recommendation system. The more the data available the better the 
recommending results.

**2. Pre-processing:**

In the pre-processing stage, Filtering and making ready the data for the project, we will make some 
changes such as, we will build tags that will describe the data and help us to calculate its similarity 
with other data.

**2.1 System designing:**

In this system design phase, we design the system which is easily understood by the end-user i.e., 
user friendly.We design some UML diagrams and data flow diagrams to understand the system flow 
and system module and sequence of execution.

**3. Model implementation and testing:**

We will create a framework of data that will coordinate with the code this phase involves the core 
part of our project that is coding and model designing. The model will make sure the project works 
well at the local level.The different test cases are performed to test whether the project module is 
giving the expected outcome in the assumed time.

**4. Website designing:**

After we have created a working model, we will create the same into a website. This stage will 
involve designing an immersive UI.

**Future Scope**
 
In the proposed approach, It has considered Genres of movies but, in future we can also consider 
age of user as according to the age movie preferences also changes, like for example, during our 
childhood we like animated movies more as compared to other movies. There is a need to work on 
the memory requirements of the proposed approach in the future. The proposed approach has been 
implemented here on different movie datasets only. It can also be implemented on the Film Affinity 
and Netflix datasets and the performance can be computed in the future.

1. The primary goal of movie recommendation systems is to filter and predict only those 
movies that a corresponding user is most likely to want to watch.

2. Saving of time: Many people have problem selecting the alternative item of movie due to 
lack of time and due to search issues. Also movie recommendations from friends can be 
time consuming. The system helps in saving lots of time.
