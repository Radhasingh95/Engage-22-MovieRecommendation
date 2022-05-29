# Content-Based-Movie-Recommender-Website

![Python](https://img.shields.io/badge/Python-3.10.4-blueviolet) 

![Framework](https://img.shields.io/badge/Framework-Streamlit-red)

![API](https://img.shields.io/badge/API-TMDB-fcba03)

Content Based Recommender System recommends movies similar to the movie user choose from the list.

## Run Locally
1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/kishan0725/Movie-Recommendation-System-with-Sentiment-Analysis/blob/master/requirements.txt) file with the command `pip install -r requirements.txt`
3. Go to python notebook in the directory, run that file and 3 pkl files will be created in the directory.
4. Open your terminal from your project directory and run the file `app.py` by executing the command `streamlit run app.py`.
5. Hurray! That's it.



## Project Flow

![project flow](https://user-images.githubusercontent.com/78557327/170816926-790bf3da-10f3-4abb-909f-59b3606b7d8c.png)


## Similarity Score : 

   How does it decide which item is most similar to the item user likes? Here come the similarity scores.
   
   It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
   
## How Cosine Similarity works?
  Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  
  ![image](https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png)

### Sources of the datasets 
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

