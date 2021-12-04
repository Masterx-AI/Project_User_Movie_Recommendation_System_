# AI/ML Project - User Movie Recommendation System

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/144659174-0f00ad48-357a-4f35-b94e-a69cd53713de.jpg" style="width: 1000px;"/></p>

### Description:

This dataset (ml-latest-small) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users between March 29, 1996 and September 24, 2018. This dataset was generated on September 26, 2018.

Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

### Acknowledgements:
This dataset is taken from Kaggle, \
https://www.kaggle.com/shubhammehta21/movie-lens-small-latest-dataset

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to recommend a movie based on users ratings.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### <center> Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Data Pre-processing
3. Exploratory Data Analysis (EDA)
4. Data Manipulation
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. Data Retention after preforming preprocessing step**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/144659409-a0e8dbda-6634-4ca8-9ba9-ca81132e546b.png" /></p>
  
**2. Visualising the Ratings Distribution**
  
![image](https://user-images.githubusercontent.com/54996245/144659464-406bceae-948a-49b3-9f9b-1d13a3451f50.png)

**3. Visualising Ratings wrt Timestamp**

![image](https://user-images.githubusercontent.com/54996245/144659578-5dd5ec67-0170-441e-939d-09529503144b.png)

**4. Visualising Ratings wrt Movies**

![image](https://user-images.githubusercontent.com/54996245/144659728-91b8cbe8-5771-499b-83da-37f1a7157f88.png)

**5. Visualising Ratings wrt Users**

![image](https://user-images.githubusercontent.com/54996245/144659849-dd3ecbda-62f3-4db7-8f71-9a1f0a33e9a2.png)

  
### Here are some of the key outcomes of the project:
- The Dataset was small totally around 9724 unique movies and 1M ratings. After preprocessing 1.7% of the datasamples were dropped. 
- There were also few outliers & no duplicates present in the datset, which had to be dropped.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the featureset.
- Further filtering was done with threshold for the number of ratings per user & per movie.
- The filtered data was was quiet spare, hence it was represented with the help of CSR Matrix Representaion.
- Finally Nearest Neighbours Algorithm was employed to get the similar Movie Recommendations based on the Cosine Similarity.

