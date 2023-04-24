## Book-Recommender-System - Overview
- This project has two main objectives.
- First objective is to show **Top 20** books of taken dataset.
  - This is Popularity Based Recommender System
- And the second objective is to recommend 5 books to user entered book.
  - This is Collaborative Filtering Type of recommendation
  - And in this project the major concern was to focus on user ratings and make recommendation based on that
- At the beginning data merging and data cleaning was performed.
- **Streamlit**'framework was being used and web app was created.
- The web app was then deployed on **Streamlit Cloud**.
- Link: https://prachipatel15-book-recommender-system-app-batk0m.streamlit.app/

## Data
https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset
- There is 3 csv files available for the project.
  - Books.csv
  - Ratings.csv
  - Users.csv
- After downloading 3 of them, you can start cleaning and building a model.
- In this project, **Cosine Similarity** was used for building collaborative filtering recommender system.
 
## Code and Resources Used
- ***Python Version:*** 3.9
- ***Packages:*** Streamlit
- ***For Web Framework Requirements:*** ```pip install -r requirements.txt```

## Conclusion 
- Both Popularity and Collaborative firterling are working at some extend.
- In collaborative filtering, cosine similarity pays huge role and it's results were more consistent.
- Here is some of the pictures from the web app.
- ![](https://github.com/PrachiPatel15/Book-Recommender-System/blob/main/webapp-1.png)
- ![](https://github.com/PrachiPatel15/Book-Recommender-System/blob/main/webapp-2.png) 


