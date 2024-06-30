# Play Store Review Analysis using NLP
![](https://kimola.com/images/google-play-scrape-analyze-reviews-open-graph.png)
## Overview

This project aims to analyze Google Play Store reviews using Natural Language Processing (NLP) techniques. 
By leveraging sentiment analysis and topic modeling, the goal is to extract actionable insights for app developers to improve user satisfaction and app performance.

## Dataset

The dataset used comprises Google Play Store reviews with the following columns:
- `reviewId`: Unique identifier for each review.
- `userName`: Name of the user who left the review.
- `userImage`: Profile image of the user.
- `content`: Textual content of the review.
- `score`: Rating given by the user (scale of 1 to 5).
- `thumbsUpCount`: Number of thumbs-up received for the review.
- `reviewCreatedVersion`: Version of the app when the review was created.
- `DateTime`: Timestamp of the review.
- `replyContent`: Content of any reply by the app developer.
- `repliedAt`: Timestamp of the reply by the app developer.
- `sortOrder`: Sorting order of the review.
- `appId`: Identifier for the reviewed app.

## Objectives

1. **Sentiment Analysis**: Classify reviews into positive, negative, or neutral sentiments.
2. **Topic Modeling**: Identify key topics and themes discussed in the reviews using Latent Dirichlet Allocation (LDA).
3. **Recommendations**: Provide actionable insights for app developers based on sentiment analysis and topic modeling results.

## Key Components

1. **Data Preprocessing**: Cleanse and preprocess textual data including tokenization, normalization, and removal of stop words.
2. **Sentiment Analysis**: Utilize TextBlob for sentiment classification and evaluate accuracy.
3. **Topic Modeling**: Implement LDA to discover latent topics within the reviews.
4. **Evaluation**: Assess model performance using accuracy metrics and classification reports.
5. **Recommendations**: Generate actionable insights and common issues based on sentiment analysis.

## Dependencies

- Python 
- Libraries: pandas, nltk, scikit-learn, textblob

## Usage

- Modify `reviews.csv` path in the script to point to your dataset.
- Customize preprocessing, modeling parameters, and analysis based on specific requirements.
- View generated insights, accuracy metrics, and recommendations in the output.

## Files Structure

```
├── Play Store Review Analysis.ipynb   # Jupyter notebook for the project
├── reviews.csv                        # Dataset file (replace with your actual dataset)
├── README.md                          # Project overview and setup instructions
```

## Conclusion

This project showcases the application of NLP techniques to analyze Google Play Store reviews, providing valuable insights for app developers to enhance user satisfaction and optimize app performance. By leveraging sentiment analysis and topic modeling, developers can make informed decisions based on user feedback.
