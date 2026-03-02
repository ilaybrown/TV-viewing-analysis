# Household Viewing Behavior Analysis

This project analyzes television viewing behavior using household demographic data and streaming event data.  
The goal is to determine whether demographic-based clustering reflects meaningful differences in content consumption patterns.

## Project Overview

The system performs:

- Demographic feature extraction and normalization  
- Dimensionality reduction using PCA  
- Household segmentation using K-means clustering  
- Subgroup construction within clusters  
- Comparative station popularity analysis using a custom `diff_rank` metric  
- Real-time incremental analysis using Spark Streaming and Kafka  

The analysis is conducted in both static and streaming environments.
