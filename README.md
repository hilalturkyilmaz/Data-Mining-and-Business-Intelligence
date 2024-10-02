This project was prepared for the 2023-2024 Data Mining and Business Intelligence course at Istanbul Medipol University's Management Information Systems Department.

The "Top 1000 IMDb Movies Dataset," which consists of the most famous and beloved films rated and ranked by IMDb users, was downloaded from Kaggle. "https://www.kaggle.com/datasets/inductiveanks/top-1000-imdb-movies-dataset"

1)Data Loading and Preview:
At the start of the project, the dataset was downloaded and uploaded to the KNIME platform. The CSV Reader node was used to import the dataset into KNIME. Once the dataset was loaded, the data was reviewed, and the columns (such as movie name, year, IMDb rating, genre, director, actors, etc.) were examined. During this stage, the general structure and quality control of the data were performed.

2)Data Cleaning:
Missing or incorrect data within the dataset was identified. For example, some films may have missing IMDb ratings or director information. These missing values were either filled in with average values or removed from the dataset using the Missing Value node.

Additionally, inconsistencies in categorical data (such as movie genres) were corrected. For better analysis, films with multiple genres were handled, and necessary data transformations were applied.

3)Data Transformation:
At this stage, some categorical data in the dataset were converted into numerical values. Particularly, features like movie genres or directors were transformed using the Category to Number node to be used in the analysis. Moreover, the date formats in the dataset were standardized to ensure consistency.

To analyze the distribution of films by year, the release years were grouped into specific ranges. This grouping step was crucial for understanding trends in movie releases.

4)Data Analysis and Exploratory Data Analysis (EDA):
After data cleaning and transformation, exploratory data analysis (EDA) was conducted. Various operations were performed to answer questions such as:

Movies by IMDb Ratings: The movies in the dataset were ranked by IMDb ratings, and the top-rated films were identified, revealing the most popular movies.
IMDb Ratings by Year: The IMDb ratings of movies were analyzed by their release year, identifying the most successful years in film history.
Analysis by Movie Genres: To see how different genres influenced IMDb ratings, the movies were grouped by genre, and the average IMDb rating for each genre was calculated.
During this stage, nodes like GroupBy, Pivoting, and Math Formula were used to classify and analyze the data.

5)Visualization:
The obtained data was visualized and reported. Various visualization nodes in KNIME were used to create the following graphs:

IMDb Rating Distribution: A histogram showing the distribution of IMDb ratings was created, revealing the most common rating range for the movies.
IMDb Ratings by Movie Genre: The effect of different movie genres on IMDb ratings was visualized. This visualization helped analyze the popularity of genres such as action, drama, and comedy.
Number of Movies by Year: A line chart showing the change in the number of movies produced by year was created. This chart helped understand the production trends in the film industry.
Visualizations were created using nodes like Bar Chart, Scatter Plot, and Line Chart, making the analysis results more comprehensible.

6)Interpreting Results:
The findings from the data analysis were interpreted. The highest-rated films by IMDb users, popular movie genres, and trends in the film industry over the years were identified. The analysis in this project led to the following key findings:

The highest-rated films on IMDb are generally in the drama and biography genres.
Films released between 1990 and 2010 are the most highly rated and beloved by IMDb users.
Although action and science fiction films tend to have high IMDb ratings, the average rating for comedy and romantic comedy genres is lower.

7)Conclusion and Future Work:
This study, which conducted a data mining project on IMDb's top 1000 films, was successfully completed. In the future, more detailed analyses can be conducted using larger datasets and incorporating additional data sources like social media interactions and viewer comments. Furthermore, machine learning techniques can be employed to develop models that predict IMDb ratings for films.
