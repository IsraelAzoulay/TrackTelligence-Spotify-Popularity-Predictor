# TrackTelligence: Spotify Popularity Predictor
This repository contains a data science project designed to analyze and predict the popularity of Spotify songs based on their audio features. The project follows a structured workflow, including exploratory data analysis (EDA), clustering and predictive modeling. The implementation adheres to the specific requirement of using `statsmodels` for model training and `scikit-learn` for preprocessing, providing a balance of statistical interpretability and modern analysis techniques.

## Key Features
- **Data Source:** Spotify dataset containing audio features and metadata for songs, sourced from [Spotify Songs Dataset from TidyTuesday](https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-01-21/spotify_songs.csv).
- **Framework:** Python-based analysis leveraging:
  - `pandas`, `matplotlib`, `seaborn` and more for data manipulation and visualization.
  - `scikit-learn` for preprocessing and evaluation.
  - `statsmodels` for statistical modeling.
- **Objective:** To develop a data analysis pipeline that accurately predicts Spotify song popularity.
- **Development Environment:** The analysis and modeling were developed in Jupyter Notebooks and are presented as HTML files for seamless exploration and visualization.

## Repository Contents
- **notebooks/EDA_Supporting_Notebook:** Performs exploratory data analysis (EDA) to uncover patterns and relationships in song features.
- **notebooks/Clustering_Supporting_Notebook:** Applies clustering techniques to group songs based on feature similarities.
- **notebooks/Modeling_Supporting_Notebook:** Builds and evaluates predictive models using statsmodels to determine a song's popularity score.
- **notebooks/Main_Notebook**: Integrates all components (EDA, clustering and modeling) into a streamlined workflow, providing a cohesive summary of the analysis.

## Getting Started
1. **Clone the Repository:**
git clone https://github.com/IsraelAzoulay/TrackTelligence-Spotify-Popularity-Predictor.git
3. **Navigate to the Project Directory:**
cd TrackTelligence-Spotify-Popularity-Predictor
4. **Open the HTML Files:**
   The repository contains HTML versions of the notebooks, which can be opened directly in your web browser.
   
## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License.
