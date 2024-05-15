

# Brewed Awakening - Beer Reviews Analysis
---
## Introduction

Welcome to the **Brewed Awakening** project! This project analyzes a comprehensive dataset of beer reviews from Beer Advocate. The dataset includes 1.5 million observations from 1996 to 2012, covering 13 different features. The goal is to uncover insights into how various beer attributes affect their reception by consumers and identify factors contributing to the success or failure of beer brands.

## Table of Contents

1. [Data Set](#data-set)
2. [Questions of Interest](#questions-of-interest)
3. [Data Processing](#data-processing)
   - Data Cleaning
   - Data Clustering
4. [Data Analysis](#data-analysis)
5. [Conclusion](#conclusion)
6. [Future Scope](#future-scope)

## Data Set

The dataset used in this project is sourced from Beer Advocate, a blog site where users can rate and review beers. The data includes:
- Reviews of approximately 6,000 distinct breweries.
- Features such as aroma, appearance, palate, taste, and overall impressions, rated on a scale of 0 to 5.

**Explanation**: This section provides an overview of the dataset, including its source and key features. It highlights the scale and scope of the data being analyzed.

## Questions of Interest

1. Does alcohol content influence the overall beer rating? If yes, how?
2. Which beer styles consistently resonate with consumers?
3. What features significantly contribute to a beer's success as a brand?
4. Can we pinpoint factors leading to the poor reception of a beer brand?

**Explanation**: This section outlines the key research questions guiding the analysis. These questions focus on understanding the impact of alcohol content, identifying popular beer styles, and determining success factors and potential pitfalls for beer brands.

## Data Processing

### Data Cleaning

1. Checking for null values and treating missing values.
   - Replacing missing 'brewery_name' and 'review_profilename' values with 'unknown'.
   - Imputing null values in 'beer_abv'.
2. Correcting data types and formats.
3. Handling duplicate reviews by keeping the latest review for each user.

**Explanation**: Data cleaning ensures the dataset is accurate and consistent. This involves handling missing values, correcting data types, and removing duplicate entries to maintain data integrity.

### Data Clustering

1. Label encoding the categorical variables.
2. Scaling numerical features.
3. Determining the number of clusters.
   - Classifying beers based on quality (Poor, Decent, Good, Best) and alcohol strength (Low, Mild, Strong, Extreme).

**Explanation**: Data clustering involves organizing the data into meaningful groups. This step includes converting categorical data into numerical form, scaling features, and identifying clusters to categorize beers based on quality and alcohol content.

## Data Analysis

1. **Correlation Heatmap**: Identifying relationships between different features.
2. **Distribution of Review Scores**: Analyzing how review scores vary for each feature across different clusters.
3. **Distribution of Beer Styles**: Examining the distribution of various beer styles by cluster.

**Explanation**: Data analysis involves visualizing and interpreting the data to extract insights. Techniques like correlation heatmaps help identify relationships between features, while analyzing the distribution of review scores and beer styles provides a deeper understanding of consumer preferences.

## Conclusion

- Identified the extent to which each attribute of a beer affects its reception by consumers.
- Determined which beer styles consistently resonate with consumers and how characteristics vary across segments.
- Provided insights into the success and failure of beers in the market.

**Explanation**: The conclusion summarizes the key findings from the analysis, highlighting how different attributes influence consumer reception and identifying popular beer styles. It also provides insights into factors contributing to the success or failure of beers in the market.

## Future Scope

- Expand the analysis to include more recent data for trends over time.
- Incorporate additional features such as geographic information to analyze regional preferences.
- Utilize advanced machine learning techniques to predict future beer trends and consumer preferences.

**Explanation**: This section outlines potential future directions for the project. Suggestions include updating the dataset with more recent data, incorporating geographic information for regional analysis, and applying advanced machine learning techniques for predictive analysis.

## Credits

This project uses a dataset from Beer Advocate, available on Kaggle. Presentation templates and visual assets were created by Slidesgo, including icons by Flaticon and infographics & images by Freepik.

**Explanation**: The credits section acknowledges the sources of data and visual assets used in the project, giving proper credit to the creators and contributors.

---
