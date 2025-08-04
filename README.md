# Zomato Restaurant Clustering and Sentiment Analysis

## Project Overview

This project focuses on analyzing Zomato restaurant data to identify meaningful clusters and perform sentiment analysis on customer reviews. The objective is to gain insights into restaurant groupings based on various attributes and understand customer sentiments using Natural Language Processing (NLP) techniques.

## Datasets Used

1. **Zomato Restaurant Names and Metadata.csv** - Contains restaurant details such as name, location, rating, price range, cuisine type, and other metadata.
2. **Zomato Restaurant Reviews.csv** - Includes customer reviews and ratings given to different restaurants.

## Objectives

- Perform Exploratory Data Analysis (EDA) to understand the dataset.
- Implement clustering techniques to categorize restaurants.
- Conduct sentiment analysis on customer reviews.
- Visualize key findings using data visualization techniques.

## Methodology

### 1. Data Preprocessing

- Checked for missing values and handled them appropriately.
- Converted categorical features into numerical values using encoding.
- Standardized and normalized numerical features.

### 2. Exploratory Data Analysis (EDA)

- Performed univariate, bivariate, and multivariate analysis.
- Visualized distributions, correlations, and trends in the data.

### 3. Clustering Restaurants

- Applied **K-Means Clustering** and **DBSCAN** to group similar restaurants based on attributes such as price, rating, and cuisine type.
- Used the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters.

### 4. Sentiment Analysis on Customer Reviews

- Preprocessed text data (removal of stopwords, tokenization, and stemming).
- Applied **VADER Sentiment Analysis** to classify reviews as Positive, Negative, or Neutral.
- Used **WordCloud** to visualize frequent words in customer reviews.

## Key Findings

- Restaurants were grouped into meaningful clusters based on price range and customer ratings.
- Sentiment analysis showed a correlation between ratings and review polarity.
- Visualization techniques helped uncover trends in popular cuisines and high-rated locations.

## Tools & Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, NLTK, WordCloud
- **Visualization:** Tableau (for additional insights)
- **Machine Learning Techniques:** Clustering (K-Means, DBSCAN), NLP (VADER Sentiment Analysis)

## Conclusion

The project successfully provided insights into restaurant groupings and customer sentiments. The clustering model identified key patterns, while sentiment analysis highlighted the importance of reviews in shaping customer perceptions.

## Future Enhancements

- Implement **Topic Modeling** (LDA) for better review analysis.
- Improve clustering by incorporating **geographical coordinates**.
- Use **deep learning-based NLP models** for enhanced sentiment classification.

## Author

Dhivya Rajesh

## Acknowledgments

- Data sourced from Zomato.
- Special thanks to AlmaBetter for providing guidance on data science methodologies.

