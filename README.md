# Spotify Music Genre Recommendation System

## Overview
This project builds a machine learning model to classify Spotify songs into genres using audio features and recommend songs based on genre.

## Dataset
Dataset sourced from Kaggle: Spotify Tracks Dataset.

Features used:
- danceability
- energy
- loudness
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo

## Model
Random Forest Classifier

Accuracy Achieved:
~70–80%

## Workflow
1. Data cleaning
2. Feature selection
3. Label encoding
4. Feature scaling
5. Train/test split
6. Model training
7. Model evaluation
8. Song recommendation

## Technologies Used
Python  
Pandas  
Scikit-learn  
Matplotlib  
Seaborn  

## Example Recommendation

Input Genre:
Pop

Output:
Song recommendations from dataset.

## Future Improvements
- Build a Streamlit web app
- Integrate Spotify API
- Deploy recommendation system
