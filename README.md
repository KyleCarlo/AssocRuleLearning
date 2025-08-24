# Discovering Musical Trends: A Spotify Data Mining Project
This repository contains the source code for a major course project on association rule learning. The project utilizes a Spotify tracks dataset to discover interesting relationships and patterns within the data, which can be used to generate insights into music consumption and characteristics.

# Collaborators
- Kyle Carlo Lasala
- Katrina Bianca Roco
- Antonio Jose Maria Lorenzo
- Charles Joseph Hinolan

# Methodology
The notebook outlines the process of applying association rule learning to the Spotify dataset:

1. Preliminaries: All necessary libraries are imported, with specific instructions provided for installing the PyFIM library if it is not already present.

2. Data Loading and Preprocessing: The Spotify dataset is loaded into a Pandas DataFrame. The data is then prepared for analysis, which likely involves discretizing continuous variables (e.g., popularity, danceability) into categorical bins to facilitate the discovery of association rules.

3. Association Rule Mining: Algorithms from the PyFIM library are applied to the preprocessed data to identify frequent itemsets and derive meaningful association rules.

4. Analysis and Insights: The discovered rules are analyzed to uncover interesting relationships between different attributes of the songs, such as genre, popularity, and acoustic features. The project also discusses the limitations and implications of the findings.

This project demonstrates a practical application of association rule learning to a real-world dataset, providing valuable insights into data mining techniques.