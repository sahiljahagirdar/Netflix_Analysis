![Netflix](https://github.com/user-attachments/assets/97149e98-dbc7-4a8e-86e9-a934b50ecb29)



Title : Netflix Analysis

Project Overview

Introduction:
- This project analyzes Netflix data to identify trends in genres, content distribution, and other key insights using Python and visualizations.

Data Description:

The Dataset Contains following columns:
- Release_Date - Release Date of a particular Movie.
- Title	Overview - Title of that movie.
- Popularity - Movie Popularity .
- Vote_Count - How many votes for a particular movie.
- Vote_Average - Movie Votes
- Original_Language - Original Language of the movie.
- Genre - movie Genre.
- Poster_Url - URL of that particular movie.

Tools Used
- Python (pandas, Matplotlib, Seaborn)
- Jupyter Notebook

Exploration summary:
- we have a dataframe consisting of 9827 rows and 9 columns
- out dataset looks a but tidy with no NaN nor duplicate values.
- Release_date columns need to be casted into date time and to extract only the year value.
- overview, original_language and poster-Url wouldn't be so useful analysis, so we'll drop them.
- there is noticable outliners in popularity column
- vote_average better be categorised for proper analysis
- Genre column has coma seperated values and white spaces that needs to be handled and casted into category.Exploration Summary


Exploratory Analysis (EDA) on dataset:

Step 1:
- Overview of the Dataset:
- <img width="1179" alt="Image" src="https://github.com/user-attachments/assets/2eebf103-c5a1-4aa8-9ac4-27c9592e35b3" />

Step 2:
- df.info() : Overview about the dataset
- <img width="543" alt="Image" src="https://github.com/user-attachments/assets/30f3eff2-f48f-41e6-9e66-1b300baf9ef3" />

Step 3:
- Check for NULL values
- <img width="346" alt="step 3" src="https://github.com/user-attachments/assets/8d573f73-3f45-4e38-8acb-dc146a9af80e" />

step 4:
- Describe The Dataset
- <img width="395" alt="Step 4" src="https://github.com/user-attachments/assets/201fd5a4-679a-46d3-bad4-badabc047151" />

Step 5:
- Change Release_date to DateTime format and take out only year from the Dataset
- <img width="513" alt="Step 5" src="https://github.com/user-attachments/assets/28ba8a2d-cc02-42ee-a32c-bd924a4d0e81" />


Step 7:
- Replace Avg_vote with Categorical Data
- <img width="662" alt="step 8" src="https://github.com/user-attachments/assets/337b5d4b-3e83-4213-8c4d-bd3884515aac" />

Step 8:
- Dataset contains multiple Genre for single movie so split the dataset
- <img width="445" alt="Step 8" src="https://github.com/user-attachments/assets/5128c720-59e4-4c81-97a1-f71ddeca9efb" />


Questions Asked:
- Q1: What is the most frequent genre in the dataset?
- Q2:What genres has highest votes?
- Q3: What movie got the highest popularity? what's its genre?
- Q4: What movie got the lowest popularity? what's its genre?
- Q5: Which year has the most filmmed movies?


Answers:
Q1: What is the most frequent genre in the dataset?:


![Q1](https://github.com/user-attachments/assets/d300e6c8-3432-4443-8e6f-7eefc14ccec8)

Q2:What genres has highest votes?:


![Q2](https://github.com/user-attachments/assets/2646284b-ead0-459a-8988-af91210a678d)

Q3: What movie got the highest popularity? what's its genre?:


<img width="699" alt="Q3" src="https://github.com/user-attachments/assets/f671e700-31a1-4c3f-8b8a-52edc1de3b33" />

Q4: What movie got the lowest popularity? what's its genre?:


<img width="848" alt="Q4" src="https://github.com/user-attachments/assets/43d0fa97-d577-444f-a431-2506ab2a00e6" />

Q5: Which year has the most filmmed movies?


![Q5](https://github.com/user-attachments/assets/41172915-1977-4d03-8cf8-f8d49a926c83)


Conclusion:

Q1: What is the most frequent genre in the dataset?
- Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres.

Q2: What genres has highest votes ?
- we have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the highest popularity among fans by being having more than 18.5% of movies popularities.

Q3: What movie got the highest popularity ? what's its genre ?
- Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action , Adventure and Sience Fiction .

Q4: What movie got the lowest popularity ? what's its genre ?
- The united states, thread' has the highest lowest rate in our dataset and it has genres of music , drama , 'war', 'sci-fi' and history`.

Q4: Which year has the most filmmed movies?
- year 2020 has the highest filmming rate in our dataset.



























