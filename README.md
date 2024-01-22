# Sentiment Analysis Web App Using Flask and Django

## Project Overview
This project is a Sentiment Analysis Web Application built using Flask and Django frameworks. The core functionality revolves around analyzing tweets to determine their sentiment (positive, neutral, or negative) based on a logistic regression model trained on tweet data.

## Features
- **Sentiment Analysis**: Analyzes the sentiment of tweets using logistic regression.
- **Tweet Preprocessing**: Includes cleaning and preprocessing of tweets for analysis.
- **Interactive Web Interface**: Built with Flask and Django for a user-friendly experience.
- **Data Visualization**: Visualizes tweet data and sentiment analysis results.

## Prerequisites
- Python 3.x
- Flask
- Django
- NLTK
- Numpy
- Pandas
- Matplotlib (optional for additional data visualization)

## Installation and Setup
1. Ensure Python 3.x is installed.
2. Install Flask, Django, NLTK, Numpy, and Pandas:
   ```bash
   pip install Flask Django nltk numpy pandas
   ```
3. Clone the repository or download the source code.

## Usage
1. Start the Flask server:
   ```bash
   python app.py
   ```
2. Access the web application through the provided local URL (usually `http://127.0.0.1:5000/`).

## Code Structure
- `app.py`: Main Flask application file with routes and sentiment analysis logic.
- `model.py`: Contains the logistic regression model and related functions.
- `templates/`: HTML templates for the Flask web interface.
- `static/`: Folder for static files used in the web application.

## Functionality Details
- The application uses NLTK for tweet preprocessing and logistic regression for sentiment analysis.
- Users can input a tweet or select from predefined examples to analyze sentiment.
- The logistic regression model is trained on tweet data, providing accurate sentiment predictions.
- The Django setup ensures smooth management and scalability of the web application.

## Known Limitations
- The sentiment analysis is currently limited to English language tweets.
- The logistic regression model might not capture the nuances of complex sentences or slang.

## Thank you
- Pianalytix for creating their Data Science Bundle course.
