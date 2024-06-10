# Movie Recommendation System

This repository contains a Movie Recommendation System built using machine learning techniques. The system suggests movies based on user preferences and historical data.

## Files in the Repository

1. **Movie_recommendation.ipynb**: Jupyter notebook that contains the implementation of the movie recommendation system. It includes data preprocessing, model training, and evaluation.

2. **app.py**: Python script to run the web application. This file contains the Streamlit application code to serve the recommendation system as a web service.

3. **main.py**: Main Python script to run the recommendation system. This file integrates various components of the system and executes the recommendation algorithm.

4. **movies.pkl**: Serialized file containing the movie data. This file is used to load the movie dataset required for the recommendation system.

5. **movies_dict.pkl**: Serialized file containing a dictionary of movies. This dictionary is used for quick lookup and processing of movie information.

## Datasets

This project uses the TMDB 5000 Movie Dataset available on Kaggle. Make sure to download the dataset and place the CSV files in the appropriate directory.

1. **tmdb_5000_movies.csv**: Contains metadata for 5000 movies from The Movie Database (TMDB).
2. **tmdb_5000_credits.csv**: Contains the cast and crew information for the same 5000 movies.

You can download the dataset from [Kaggle TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata).

## Setup and Installation

### Prerequisites

- Python 3.6 or above
- Jupyter Notebook
- Streamlit

### Installation Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/nandutejaswini/movie-recommendation-system.git
   cd movie-recommendation-system
### Usage
#### Jupyter Notebook
Open the Movie_recommendation.ipynb notebook in Jupyter.
Follow the steps in the notebook to preprocess data, train the model, and evaluate its performance.
You can also modify the notebook to try different algorithms or preprocessing techniques.

### Web Application
1. Run the Streamlit app using streamlit run app.py.
2. Open your web browser and navigate to the URL provided by Streamlit (usually http://localhost:8501/).
3. Use the web interface to get movie recommendations based on your input.

###   How the Streamlit App Works
1. Select a movie from the dropdown menu in the Streamlit app.
2. The system will recommend five movies similar to the selected movie.
3. Example movies to select from: "Spider-Man 3", "Spider-Man 2", "Spider-Man", "The Amazing Spider-Man", "The Amazing Spider-Man 2", "Arachnophobia".

### Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new features to add.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgments
This project uses data from MovieLens and TMDB 5000 Movie Dataset.
