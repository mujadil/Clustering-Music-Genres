# Clustering Music Genres with Machine Learning
## Project Overview

This project demonstrates the use of machine learning to perform clustering analysis on music genres. The goal is to group songs based on the similarities in their audio characteristics using the K-means clustering algorithm.
Dataset

The dataset used for this project contains information about popular songs on Spotify, including various audio features such as:

    Beats Per Minute (BPM)
    Energy
    Danceability
    Loudness (dB)
    Liveness
    Valence
    Acousticness
    Speechiness
    Popularity

You can download the dataset from Spotify-2000.csv.
## Project Structure

    clustering_music_genres.py: This is the main script that loads the dataset, preprocesses it, and performs clustering analysis using the K-means algorithm.
    requirements.txt: This file contains the list of Python libraries required to run the project.

### Steps

    Load the Dataset: The dataset is loaded using Pandas.

    Data Preprocessing: Unnecessary columns (like index) are dropped, and the dataset is normalized.

    Correlation Analysis: A correlation matrix is generated to understand the relationships between different audio features.

    Clustering: The K-means clustering algorithm is applied to the audio features to group similar songs together.

    Visualization: The clusters are visualized using a 3D scatter plot created with Plotly.

## Installation

To run this project, make sure you have Python installed. You can install the required libraries using the following command:


    pip install -r requirements.txt

## Usage

Run the clustering_music_genres.py script to perform the clustering analysis:


    python clustering_music_genres.py

This will output the clustered data and a 3D visualization of the clusters based on selected audio features.

## Visualization

The clusters can be visualized using Plotly's 3D scatter plot, where each cluster is represented by a different color.

## Conclusion

This project showcases how to use machine learning techniques to cluster music genres based on audio characteristics. The K-means algorithm effectively groups similar songs, which can be useful for music recommendation systems.
