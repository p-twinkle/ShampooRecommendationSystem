# ShampYou: A Personalized Shampoo Recommender

## Project Overview

ShampYou is a data-driven shampoo recommendation system designed to help users navigate the vast array of shampoo products available in the market. As of October 2024, Influenster.com listed over 22,000 shampoo products, making it challenging for consumers to find the right product for their needs[1].

## Features

- **Personalized Recommendations**: Provides tailored shampoo suggestions based on user preferences and hair needs[1].
- **Price Consideration**: Incorporates product pricing to offer affordable alternatives[1].
- **Multi-faceted Analysis**: Utilizes various data analysis techniques including word frequency, lift analysis, and similarity measures[1].
- **Language Processing**: Translates reviews from multiple languages to English for comprehensive analysis[1].

## Data Sources

- Top 100 shampoos from Influenster.com, including:
  - Total review count and average rating
  - 50 most recent ratings and reviews
- 10,000 product prices (fuzzy matched to Influenster data)[1]

## Analysis Process

1. **Review Translation**: Convert non-English reviews to English
2. **Word Frequency Analysis**: Count unique words in reviews
3. **Product Popularity Assessment**: Investigate long-tail effect based on review counts
4. **Attribute Lift Analysis**: Identify top attributes and their co-mentions
5. **Similarity and Sentiment Analysis**: Use cosine similarity, Vader sentiment, and spaCy for recommendations
6. **Price Integration**: Enhance recommendations with price data

## Recommendation Profiles

The system can generate recommendations for various user profiles, such as:
- Soft, Shiny, Silky hair
- Frizz-Free, Shiny, Affordable options
- Curly, Nourishing, Fruity preferences
- Herbal, Hydration, Volume needs[1]

## Future Work

- Obtain more standardized pricing data
- Implement customer segmentation for new product launches
- Conduct market basket analysis for product bundling
- Develop symptom-based recommendations (e.g., dandruff, itchiness)

## Team Members

- Dameli Aziken
- Twinkle Panda
- Vishwa Patel
- Sneha Sastry Rayadurgam
- Kimberly Simmonds
