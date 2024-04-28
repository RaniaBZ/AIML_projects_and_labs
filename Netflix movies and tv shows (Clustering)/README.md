# Netflix_Movies_And_TvShows_Clustering/Unsupervised machine Learning Project

# Objective
### The objective of this project is to analyze and cluster a dataset related to Netflix. The dataset consists of various attributes associated with Netflix shows and movies, such as title, genre, release year, duration, rating, and others. The aim is to explore patterns and similarities among the content available on the platform and group them into meaningful clusters.

# Dataset
### This dataset contain information about various TV shows and movies available on Netflix, including details like the production country, release year, rating, duration, genre, and a description of each title. It consists of 12 columns and 7787 rows.

# Description
### show_id : Unique ID for every Movie / Tv Show

### type : Identifier - A Movie or TV Show

### title : Title of the Movie / Tv Show

### director : Director of the Movie

### cast : Actors involved in the movie / show

### country : Country where the movie / show was produced

### date_added : Date it was added on Netflix

### release_year : Actual Releaseyear of the movie / show

### rating : TV Rating of the movie / show

### duration : Total Duration - in minutes or number of seasons

### listed_in : Genere

### description: The Summary description

# Core of the project
### To begin with, the dataset will be preprocessed by handling missing values, removing irrelevant columns, and transforming categorical variables into numerical representations. Feature engineering techniques may also be applied to extract useful information from the existing attributes.

### Next, exploratory data analysis (EDA) techniques will be utilized to gain insights into the dataset. Visualizations and statistical summaries will be used to understand the distribution of variables, identify any trends, and explore relationships between different features.

### Once the dataset has been thoroughly analyzed, clustering algorithms such as k-means, hierarchical clustering, or density-based spatial clustering will be employed. These algorithms will group similar Netflix shows and movies together based on their attributes. The optimal number of clusters will be determined using techniques like the elbow method or silhouette analysis.

### After the clustering process, the results will be evaluated and interpreted. The clusters will be analyzed to understand the common characteristics and patterns within each group. This analysis will provide valuable information for Netflix in terms of content categorization, recommendation systems, and content acquisition strategies.

### Finally, the findings and insights from the clustering analysis will be summarized and presented in a clear and concise manner. Visualizations, charts, and graphs will be used to effectively communicate the outcomes of the project. Recommendations may also be provided based on the identified clusters, suggesting potential improvements or strategies for Netflix to enhance user experience and content offerings.

# Conclusion
### It is interesting to note that the majority of the content available on Netflix consists of movies. However, in recent years, the platform has been focusing more on TV shows.

### Most of these shows are released either at the end or the beginning of the year.

### The United States and India are among the top five countries that produce all of the available content on the platform.

### Indian actors dominate Netflix movies, while popular Indian actors are absent from TV shows.

### When it comes to content ratings, Adult Content tops the charts, indicating that mature content is more popular on Netflix.

### Most movies on Netflix have durations between 80 to 120 minutes, while TV shows commonly have one or two seasons.

### The optimal number of clusters we are getting from K-means is 8, whereas for Agglomerative Hierarchical Clustering the optimal number of clusters are found out to be 7.

### We chose Silhouette Score as the evaluation metric over distortion score because it provides a more intuitive and interpretable result. Also Silhouette score is less sensitive to the shape of the clusters.

### Using this data, a Content based recommender system was created using cosine similarity, which provided recommendations for Movies and TV shows.

# Future work
### Integrating this dataset with external sources such as IMDB ratings,books clsutering ,Plant based Type clustering can lead to numerous intriguing discoveries.

### By incorporating additional data, a more comprehensive recommender system could be developed, offering enhanced recommendations to users. This system could then be deployed on the web for widespread usage.
