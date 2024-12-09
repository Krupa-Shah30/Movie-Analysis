
# Movie Analysis using PySpark

## Project Overview

This project leverages PySpark to conduct a comprehensive analysis of a movie dataset, aiming to predict IMDB ratings and uncover insights into factors influencing movie success. The analysis encompasses both supervised and unsupervised machine learning techniques, providing valuable information for filmmakers, producers, and industry professionals.

## Key Features

- Prediction of high IMDB ratings (>7) with 72.44% accuracy
- Analysis of genre combinations and their impact on ratings
- Exploration of director-genre relationships
- Investigation of actor-director collaborations using graph analysis
- Movie clustering for personalized recommendations

## Dataset

The dataset includes 3,598 movies with 28 variables, covering aspects such as:
- Movie details (color, duration, budget, gross revenue)
- Cast and crew information (director, actors, Facebook likes)
- Social media metrics (Facebook likes for movie, cast, and crew)
- IMDB-specific data (user reviews, votes, and scores)

## Methodology

1. Data Cleaning and Preprocessing
   - Handling missing values
   - Standardizing data formats

2. Feature Engineering
   - Creating new features (e.g., "popular actor 1")
   - Applying transformations (min-max scaling, one-hot encoding)

3. SQL Analysis using PySpark
   - Extracting insights on director-genre relationships
   - Analyzing genre combination impacts on ratings

4. Supervised Learning
   - Model selection (Decision Tree, Random Forest)
   - Hyperparameter tuning
   - Performance evaluation

5. Unsupervised Learning
   - Clustering similar movies

6. Graph Analysis
   - Investigating actor-director-movie relationships

## Key Findings

- Animation and drama genre combination yields the highest average IMDB rating (7.36)
- Identified patterns in directorial influence across genres
- Uncovered collaboration networks within the film industry
- Developed a predictive model for high IMDB ratings

## Technologies Used

- PySpark
- Python
- SQL
- Machine Learning (Supervised and Unsupervised)
- Graph Analysis

## Future Work

- Incorporate more recent data to capture evolving trends
- Explore additional machine learning algorithms for improved accuracy
- Integrate external data sources for richer analysis

## Contributors

- Jainam Chhadwa
- Krupa Shah
- Hitaishi Joshi

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
