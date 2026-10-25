# DSA 4060XA - Week 6 Recommender Systems Evaluation

**Student Name:** [Ogutu Rufinus]  
**Student ID:** [670827]  

## Lab Objective
To implement, evaluate, and compare three recommender systems (Popularity Baseline, Content-Based Filtering, and Item-Based Collaborative Filtering) across rating prediction, ranking quality, catalogue coverage, novelty, and diversity metrics.

## Models Compared
1. Popularity Baseline
2. Content-Based Filtering
3. Item-Based Collaborative Filtering

## Best Model Results
- **Best Model for Rating Prediction:** Item-Based Collaborative Filtering (MAE: 0.924, RMSE: 1.070).
- **Best Model for Ranking:** Content-Based Filtering / Popularity Baseline.
- **Coverage & Diversity:** Item-Based CF achieved 85% coverage and 0.780 diversity.

## Final Recommended Model
Item-Based Collaborative Filtering.

## Limitations
1. Extreme data sparsity in small user-item interaction matrices.
2. Positive rating skewness / reporting bias.
3. Limited metadata features (genres only).
