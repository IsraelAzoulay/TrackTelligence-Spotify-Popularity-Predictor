# TrackTelligence: Spotify Popularity Predictor
This repository contains a data science project designed to analyze and predict the popularity of Spotify songs based on their audio features. The project follows a structured workflow, including exploratory data analysis (EDA), clustering and predictive modeling. The implementation adheres to a **specific requirement** of using `statsmodels` for model training and `scikit-learn` for preprocessing, providing a balance of statistical interpretability and modern analysis techniques.

---

## Key Features
- **Data Source:** Spotify dataset containing audio features and metadata for songs, sourced from [Spotify Songs Dataset from TidyTuesday](https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-01-21/spotify_songs.csv).
- **Framework:** Python-based analysis leveraging:
  - `pandas`, `matplotlib`, `seaborn` and more for data manipulation and visualization.
  - `scikit-learn` for preprocessing and evaluation.
  - `statsmodels` for statistical modeling.
- **Objective:** To develop a data analysis pipeline that accurately predicts Spotify song popularity.
- **Development Environment:** The analysis and modeling were developed in Jupyter Notebooks and are presented as HTML files for seamless exploration and visualization.

---

## Repository Contents
- **notebooks/EDA_Supporting_Notebook:** Performs exploratory data analysis (EDA) to uncover patterns and relationships in song features.
- **notebooks/Clustering_Supporting_Notebook:** Applies clustering techniques to group songs based on feature similarities.
- **notebooks/Modeling_Supporting_Notebook:** Builds and evaluates predictive models using statsmodels to determine a song's popularity score.
- **notebooks/Main_Notebook**: Integrates all components (EDA, clustering and modeling) into a streamlined workflow, providing a cohesive summary of the analysis.

---

## Getting Started

Follow the steps below to clone the repository and access the notebooks locally:

### 1. Clone the Repository
To get started, clone the repository to your local machine:
```bash
git clone https://github.com/IsraelAzoulay/TrackTelligence-Spotify-Popularity-Predictor.git
```

### 2. Navigate to the Project Directory
Change into the project directory:
```bash
cd TrackTelligence-Spotify-Popularity-Predictor
```

### 3. Access the Notebooks
The notebooks are too large to preview directly on GitHub. You can download and view them locally by following these steps:
1. Navigate to the `notebooks` folder in the repository.
2. Click on the notebook you want to view (e.g., `notebooks/EDA_Supporting_Notebook.html`).
3. When the raw data opens in a new browser tab:
   - **Windows/Linux:** Press `Ctrl + S` to save the file.
   - **Mac:** Press `Cmd + S` to save the file.
4. Open the saved file in your web browser to explore the notebook.

---

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

---

## License
This project is licensed under the MIT License.
