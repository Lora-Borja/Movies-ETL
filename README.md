# Movies-ETL

## Project Overview
Using the Extract, Transform, Load (ETL) process an automated pipeline from raw movies data (from the Wikipedia data, the Kaggle metadata, and the MovieLens rating data) to a SQL database was created for this project, which was carried out for the team at a hypothetical company called, Amazing Prime Video, an online video streaming service. The team wanted to develop an algorithm to predict which low budget movies being released will become popular so that they can buy the streaming rights at a low cost. A hackathon event was called in order to facilitate this project with the following deliverables. 

## The Deliverables
* Deliverable 1: Write an ETL Function to Read Three Data Files

This was achieved under the ETL_function_test.ipynb file uploaded in this repository with codes showing a function that reads in the three data files and creates three separate DataFrames.

* Deliverable 2: Extract and Transform the Wikipedia Data

This was achieved under the ETL_clean_wiki_movies.ipynb file uploaded in this repository with codes to expand on the first deliverable to extract and transform the Wikipedia data in a cleaner dataset, then converted into a DataFrame.

* Deliverable 3: Extract and Transform the Kaggle data & MovieLens rating data

This was achieved under the ETL_clean_kaggle_data.ipynb file uploaded in this repository. Like the second deliverable the codes were to also perform an extraction of the movie metadata from Kaggle as well as the MovieLens ratings data and transform it in a cleaner dataset, then converted into separate DataFrames. The Kaggle metadata DataFrame and the Wikipedia movies DataFrame was then merged to create the movies_df DataFrame. Finally, the MovieLens rating data DataFrame was merged with the movies_df DataFrame to also create the movies_with_ratings_df.

* Deliverable 4: Create the Movie Database

This was achieved under the ETL_create_database.ipynb file uploaded in this repository. With these codes the movies_df DataFrame and MovieLens rating CSV data was uploaded to a SQL database for the team to be able to further evaluate or analyze.
