# BYTEUPRISE_ML_02
Movie Rating Prediction Model using Logistic Regression
# BYTEUPRISE_ML_02
Movie Rating Prediction Model using Logistic Regression.

# Movie rating Prediction with Logistic Regression

This repository contains a Data Science and Machine Learning project that predicts movie rating using a logistic regression model. The model leverages key features such as genres, production_companies, production_countries, release_year,movie_id,rating and rating to predict the movie rating.

# **Dataset**
The dataset used in this project is sourced from the "Movie Rating Prediction" dataset, which includes genres and rating information about movies of various genres released in different years. The dataset is provided in a CSV format (ratings.csv).

# **Features**
*user_id - id number of a particular user whobrated the movie.
*movie_id - id number a particular movie.
*rating - the rating scale goes  from 0 to 5 for a particular movie.
*genres - the genre decribes the movie in one word.
*production_companies	- the company that produced the particular movie
*production_countries	- the country where the movie was produced.
*release_year	- in which year the movie released?
*overview - an overview of the movie.

# **Project Structure**
The project is organized as follows:
* ratings.csv: The raw dataset file.
* data.dropna(): Dropping the missing values.
* data.info(): Processed data after handling the missing values.

# **Requirements**
* Python 3.x
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

# **Model Training and Evaluation**
The logistic regression model is trained using the user_id, genre, release_year and ratings.
Model evaluation metrics include:
* X_test=np.array(X_test)
* model.predict(X_test)
* comparing our model with the test data = Y_test
