# Smartphone Recommendation System

![Smartphone Recommendation](https://avatars.mds.yandex.net/i?id=aa78e71ab6327b758c4e1a99d15fe39b_l-11379423-images-thumbs&n=13)

## Project Overview

ML-powered system identifying key smartphone features that matter most to buyers

## Key Features

- Analyzes 33 different smartphone models from various brands
- Considers technical specs (RAM, camera, battery, etc.) and user characteristics (age, gender, occupation)
- Identifies most important features for recommendations
- Visualizes feature importance and model performance

## Dataset

The dataset contains:
- Smartphone technical specifications (brand, model, OS, memory, camera, etc.)
- User ratings (1-10 scale)
- User demographic information (age, gender, occupation)

## Implementation

```python
# Main workflow
1. Data loading and merging
2. Feature engineering (one-hot encoding)
3. AdaBoost classifier training
4. Hyperparameter tuning (n_estimators)
5. Feature importance analysis
6. Visualization of results
