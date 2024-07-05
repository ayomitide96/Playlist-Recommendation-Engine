# Playlist Continuation Using Hybrid Recommendation Engine

Welcome to the Playlist Continuation project repository! This repository contains all the files and documentation for a hybrid recommendation engine designed to enhance the user experience by continuing playlists with tracks that match user preferences and contextual variables.

## Project Overview

This project explores the development of a sophisticated music recommendation system designed to continue user playlists by predicting the next tracks that align with their musical preferences and context. Utilizing the Spotify Million Playlist Dataset, this system integrates multiple recommendation techniques to overcome the limitations of traditional systems such as over-specialization and the cold-start problem.

### Key Features:
- **Hybrid Recommendation Engine**: Combines collaborative filtering, content-based filtering, and context-aware recommendations.
- **Machine Learning Algorithms**: Implements Artificial Neural Networks (ANN), XGBoost, and Alternating Least Squares (ALS) for model training.
- **Enhanced User Experience**: Focuses on balancing user familiarity with musical diversity, providing a coherent and engaging listening experience.

## Dataset

The project uses a subset of the Spotify Million Playlist Dataset, which includes:
- User interactions with playlists
- Track metadata and features
- Playlist composition

### Dataset File: `playlist csv.csv.zip`
- **Contents**: CSV file with user, track, and playlist interaction data.
- **Columns**:
  - `user_id`: Unique identifier for each user
  - `track_id`: Unique identifier for each track
  - `playlist_id`: Unique identifier for each playlist
  - `timestamp`: Timestamp indicating when the interaction occurred

## Installation

To get started with the project, clone the repository and install the necessary dependencies:

```bash
# Clone the repository
git clone https://github.com/ayomitide96/Playlist-Recommendation-Engine.git
cd Playlist-Recommendation-Engine

# Create a virtual environment (optional but recommended)
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`

# Install required libraries
pip install -r requirements.txt
```
## Methodology

The hybrid recommendation engine integrates multiple techniques:

- **Collaborative Filtering**: Suggests tracks based on user behavior and interactions.
- **Content-Based Filtering**: Recommends tracks by analyzing the attributes and features of the music.
- **Context-Aware Recommendations**: Incorporates contextual information to enhance the recommendation relevance.

### Models Used:
- **Artificial Neural Networks (ANN)**: Captures complex patterns in user preferences.
- **XGBoost**: An efficient gradient boosting framework for ranking and classification tasks.
- **Alternating Least Squares (ALS)**: Collaborative filtering method for matrix factorization.

### Evaluation Metrics:
- **Precision and Recall**: Measure the relevance and coverage of the recommendations.
- **User Satisfaction**: Assessed through simulated feedback based on user profiles.

## Usage

You can explore the functionality of the recommendation system using the provided Jupyter Notebook.

### Steps to Use the Notebook:

1. **Start Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
### Usage Instructions

2. **Open Playlist cont preprocessing.ipynb**: Navigate to the notebook in the Jupyter interface.
3. **Run the Cells**: Execute the cells in order to preprocess data, train models, and generate recommendations.

### File Descriptions

- **Playlist cont preprocessing.ipynb**: Jupyter Notebook containing the data preprocessing steps, model training, and evaluation procedures.
- **playlist csv.csv.zip**: Zipped CSV file with the dataset used for building and testing the recommendation system.
- **requirements.txt**: Lists the Python dependencies required to run the project.
- **README.md**: This file, providing an overview and instructions for the project.

### Results

The hybrid recommendation system significantly improves playlist coherence and user satisfaction compared to traditional recommendation models. Detailed performance metrics and analysis can be found in the `Playlist cont preprocessing.ipynb` notebook.

