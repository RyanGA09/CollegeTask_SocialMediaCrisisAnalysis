# CollegeTask - Social Media Crisis Analysis

## Overview

This project focuses on analyzing social media crises by performing sentiment analysis on YouTube comments. It leverages text preprocessing, clustering, and sentiment classification to gain insights into public perception.

## Features

- **Data Collection**: Scrapes YouTube comments using YouTube API.
- **Text Preprocessing**: Tokenization, stopword removal, stemming, and TF-IDF vectorization.
- **Sentiment Analysis**: Uses TextBlob to classify comments as Positive, Negative, or Neutral.
- **Clustering**: Applies K-Means clustering to group comments based on similarity.
- **Visualization**: Generates bar charts and word clouds for sentiment distribution.
- **Evaluation**: Computes confusion matrix, accuracy, precision, recall, and F1-score.

## Tech Stack

- Python: Main programming language (IPYNB).
- Libraries: Pandas, NumPy, Scikit-learn, TextBlob, Matplotlib, Seaborn, WordCloud.
- YouTube API: For scraping YouTube comments.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/RyanGA09/CollegeTask_SocialMediaCrisisAnalysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd CollegeTask_SocialMediaCrisisAnalysis
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up YouTube API credentials.

5. Run the script:

   ```bash
   python main.py
   ```

## Usage

1. Provide a YouTube video link for comment scraping.
2. The program processes and analyzes comments.
3. Sentiment results and clustering visualizations are displayed.
4. Evaluation metrics are generated to assess the model's performance.

## Results

Sentiment Distribution: Displays the proportion of positive, negative, and neutral comments.

Clustering Output: Groups comments based on similarity.

Performance Metrics: Accuracy, precision, recall, and F1-score.

## License

&copy; 2025 Ryan Gading Abdullah. All rights reserved.

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) for details.
