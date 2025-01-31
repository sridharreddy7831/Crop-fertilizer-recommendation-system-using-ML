# Crop Fertilizer Recommendation System

## Overview
This project provides a **Crop Fertilizer Recommendation System** based on various features. The system analyzes crop data and suggests optimal fertilizers.

## Dataset
The project uses the **Crop_recommendation.csv** dataset, which contains:
- Various soil parameters
- Weather conditions
- Crop labels

## Improvements in Week 2
### Feature Analysis Enhancement
Previously, basic column checks were performed. In **Week 2**, improvements were made to analyze the dataset more effectively:
- Used `crop['label'].value_counts()` to check the distribution of crops.
- Improved feature analysis by identifying the frequency of each crop label.
- This enhancement helps in understanding the data distribution before applying machine learning models.

## Files in This Repository
- **crop.ipynb** - Jupyter Notebook containing analysis and implementation.
- **Dataset/Crop_recommendation.csv** - The dataset used for recommendations.
- **README.md** - This documentation file.

## Next Steps
- Implement deeper insights into fertilizer recommendations.
- Optimize the model for better predictions.

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Run `crop.ipynb` in Jupyter Notebook.

## Contributions
Suggestions and improvements are welcome. Feel free to open a pull request!

