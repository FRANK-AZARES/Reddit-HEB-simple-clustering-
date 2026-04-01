# Reddit-HEB-simple-clustering-
Using Reddit’s public JSON endpoints to perform a simple, lightweight data access without using API authentication, performed a simple, unsupervised, word clustering using Term Frequency-Inverse Document Frequency (TD IDF) on a random sample of pulled posts and comments from r/HEB

## Overview
This project analyzes Reddit discussions related to HEB using NLP techniques.

## Project Workflow

### 1. Data Collection
Gathered publicly available Reddit posts and comments about HEB to capture real, unfiltered user opinions.

### 2. Data Cleaning
Raw text data is often noisy, so cleaning is needed to remove links, punctuation, and other unnecessary elements for analysis.

### 3. Turning Text into Data
Converted the cleaned text into numerical representations, allowing machine learning models to identify patterns in the language.

### 4. Finding Patterns (Clustering)
Applied a clustering algorithm to automatically group similar comments together, enabling the identification of common themes without pre-labeling the data.

### 5. Visualization
Reduced the high-dimensional text data into a 2D visualization to illustrate how different conversation groups are together.

## Methods
- Data collection via Reddit JSON endpoint
- Text preprocessing
- TF-IDF vectorization
- KMeans clustering
- PCA visualization

### NOTE: The filter text document contains profane words. The intent here is to create a list of words to exclude. Instead of displaying these words directly in the code, they are stored in the text file. The code calls the text file directly, not the words.
