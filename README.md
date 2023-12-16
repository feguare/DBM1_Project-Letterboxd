# DBM1_Project-Letterboxd
#### by Fiona Eguare & Erica Guardamagna

****IMPORTANT:*** The 'ratings.csv' file was too large to be uploaded. This file can be dowloaded directly from Kaggle [here](https://www.kaggle.com/datasets/samlearner/letterboxd-movie-ratings-data?select=ratings_export.csv). 'ratings_export.csv' can be extracted from the zip file, renamed to 'ratings.csv', and stored in the 'Final' folder alongside the other files to avoid path changes when running locally.

- This project was completed as part of the IST-4-DBM1 Databases Module at INSA Lyon.
- All data used in this project was sourced from the Kaggle '[Letterboxd Movie Ratings Data](https://www.kaggle.com/datasets/samlearner/letterboxd-movie-ratings-data)' dataset, however, the files upladed in the 'Final' folder in this repo are the final data files from this project, after the database had been set up and preprocessed.
- Due to the issues uploading the rating data, the preprocessing changes described in the report are not visible, however theses changes do not effect the quieries so the original file can still be used.
- To run:
  1. Download the 'Final' file from this Repo
  2. Get Ratings data as explainedf above
  3. Navigate to the 'ProjectLetterboxd.ipynb' in your text editor
  4. Ensure that the file paths in the 'Fetch Data' cell of the 'Setup' section of the notebook match the locations of the files on your device relative to the location of the notebook
  5. Run the 'Setup' cells, the run the desired query to see the output
- There is some variation between the queries in the notebook and the queries in the report, as some the the functions (eg. '::numeric(10:2)' to control output float precision) that we used when originally completing the project in PGAdmin would not work in SQLite.
