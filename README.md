# TiktokProject
TikTok Creator Marketplace - Personalized Sponsorship Recommendations

Project Presentation : https://anish-tiktokproject.carrd.co


# TikTok Creator Marketplace: Personalized Sponsorship Recommendations

## Overview

This project aims to bridge the gap between brands and TikTok creators using a personalized recommendation system. By leveraging comprehensive datasets and advanced algorithms, the project suggests efficient brand-creator collaborations.

## Repository Contents

### Code

1. **`TikTok_Project_Code.ipynb`**
    - **Execution Environment**: Local Machine, Jupyter Notebook
    - **Description**: 
      - Data Cleaning and Preprocessing: Prepares the raw datasets for further analysis.
      - User Behavior Analysis: Investigates how users interact with the platform.
      - Sponsorship Matching Algorithm: Develops the primary recommendation system, calculates similarity scores, and determines the best matches between brands and creators.

2. **`TikTok_Project.ipynb`**
    - **Execution Environment**: Google Colab
    - **Description**: 
      - Content Analysis: Employs both Computer Vision and Natural Language Processing (NLP) techniques to analyze and categorize the content produced by the creators.

### Datasets

1. **`cleaned_creator_dataset.csv`** & **`cleaned_brand_dataset.csv`**
    - Post data cleaning and preprocessing datasets for creators and brands respectively.

2. **`TikTok_Data_With_Features.csv`**
    - Creator dataset enriched with visual features extracted using Computer Vision from video URLs.

3. **`content_similarity_scores.csv`** & **`similarity_scores.csv`**
    - Contains the similarity scores based on content analysis. The scores indicate how well the content from a creator aligns with the brand's preferences. While both files hold similar data, `content_similarity_scores.csv` is more organized and structured.

4. **`merged_results.csv`**
    - A combined dataset that integrates similarity scores, visual features, and the original creators' dataset.

5. **`recommendations.csv`**
    - The final output CSV. It enlists creators, the brands most compatible with them, and their associated similarity scores.

## Getting Started

1. **Data Cleaning and Preprocessing**: 
    - Start with the `TikTok_Project_Code.ipynb` notebook on your local machine. This will generate `cleaned_creator_dataset.csv` and `cleaned_brand_dataset.csv`.

2. **Content Analysis**:
    - Upload `cleaned_creator_dataset.csv` to Google Colab and run `TikTok_Project.ipynb`. This process adds visual features to the dataset and computes similarity scores. The results will be saved as `TikTok_Data_With_Features.csv`, `content_similarity_scores.csv`, and `similarity_scores.csv`.

3. **Recommendation Generation**:
    - Continue with the latter sections of `TikTok_Project_Code.ipynb` on your local machine, which utilize the generated files from the previous step, and yield the final recommendations in `recommendations.csv`.

## Conclusion

The system ensures a win-win scenario: creators find genuine sponsors, brands connect with effective influencers, and TikTok can explore a potential revenue stream. With further refinement and more data sources, the potential of this recommendation system can be further unlocked.


## Note 

This repository does not include the media files which contains videos of content creators and influencers. User may download it from Tiktok.
