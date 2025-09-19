# Netflix-Movies-and-TV-Shows-Clustering

The Netflix Movies and TV Shows Clustering Project aims to cluster similar movies and TV shows available on Netflix into different clusters based on their content. The project uses unsupervised learning and Natural Language Processing (NLP) techniques to analyze the dataset, including K-Means, Hierarchical clustering, and DBSCAN algorithms.

# Dataset
his dataset consists of tv shows and movies available on Netflix as of 2020.
 
 Attribute Information :
 show_id : Unique ID for every Movie / Tv Show
 type : Identifier - A Movie or TV Show
 title : Title of the Movie / Tv Show
 director : Director of the Movie / TV Show
 cast : Actors involved
 country : Country of production
 date_added : Date it was added on Netflix
 release_year : Actual Release year of the movie / TV show
 rating : TV Rating of the movie / TV show
 duration : Total Duration in minutes or number of seasons
 listed_in : Geners
 description : The Summary description

 # Techniques: Data Cleaning and Data Preprocessing, Exploratory Data Analysis, Model Building and Models Evaluation
 # Model Building
1. K-Means Clustering
2. Hierarchical Clustering
3. DBSCAN Clustering

#  The K-Means Clustering model has the highest Calinski-Harabasz score out of all the models (9.039247). Also, the silhouette score for the K-Means Clustering model is 0.004634,
 which is close to one compared to other models, indicating that it can cluster Movies and TV shows perfectly based on the content.
 - The K-Means Clustering model is the optimal model and well-trained for clustering TV shows and movies based on the content due to its high
 Calinski-Harabasz score (9.039247) and silhouette score (0.004634), which are close to 1 than other builded models.
