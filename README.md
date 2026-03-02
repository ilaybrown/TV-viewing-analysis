# Household Viewing Behavior Analysis

This project analyzes large-scale TV viewing data using household demographic features and streaming event logs.  
The objective is to evaluate whether demographic-based clustering reveals meaningful differences in content consumption patterns.

## Project Overview

The pipeline includes:

- Demographic feature extraction and normalization  
- Dimensionality reduction using PCA  
- Household segmentation using K-means clustering  
- Subgroup construction within clusters  
- Comparative station popularity analysis using a custom `diff_rank` metric  
- Real-time incremental analysis using Spark Streaming and Kafka  

The analysis is conducted in both static and streaming environments.
