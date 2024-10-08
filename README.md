# Movie-Recommender-System
# Movie Recommender System
🎬 A Movie Recommender System that suggests movies based on user preferences using the TMDB dataset and Streamlit for the web interface.
## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-works)
- [Contributing](#contributing)
- [License](#license)
## Introduction
This project is designed to recommend movies to users based on their selected movie. It utilizes a content-based filtering approach, leveraging the TMDB dataset to analyze similarities between movies and provide personalized suggestions.
## Technologies Used
- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- TMDB API
## Dataset
The project uses the TMDB dataset, which includes two main files:
- `tmdb_5000_movies.csv`: Contains information about 5000 movies.
- `tmdb_5000_credits.csv`: Contains credits data for the movies.
You can download the dataset from [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
## Installation
To run this project, you'll need to have Python installed on your machine. Follow these steps to set up the project:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommender-system-tmdb-dataset.git
   cd movie-recommender-system-tmdb-dataset
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
3. Create a model directory and place your movie_list.pkl and similarity.pkl files inside it.
4. Set up your TMDB API key in the code (replace the API key in the fetch_poster function).
## Usage
1. To run the application, execute the following command:
    ```bash
    streamlit run app.py

## How It Works
1. Data Loading: The application loads movie data and similarity data from pickle files.
2. User Input: Users can select a movie from the dropdown menu.
3. Recommendation: The app computes movie recommendations using a content-based filtering approach, fetching movie posters from the TMDB API.
4. Display: Recommended movies and their posters are displayed in a user-friendly layout.

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License