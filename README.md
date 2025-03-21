# Probability_and_Statistics_Project

This repository contains Python implementations of various probability and statistics concepts. Each script is structured to solve a specific statistical problem.

## Project Overview

The repository includes the following problem statements:

### 1. Confidence Interval Calculation (`confidence_interval.ipynb`)
- Computes a 90% confidence interval for customer satisfaction data.
- Uses `scipy.stats.norm.ppf` to calculate the margin of error.

### 2. Probability Calculation for Car Speeds (`probability_car_speeds.ipynb`)
- Calculates the probability of a randomly selected car exceeding a given speed.
- Uses the normal distribution (mean = 75 km/h, std dev = 15 km/h).

### 3. Rainfall and Flood Probability Analysis (`rainfall_flood_analysis.ipynb`)
- Loads the `kerala.csv` dataset.
- Analyzes rainfall trends in June and July.
- Computes conditional probabilities of flooding based on rainfall data.

### 4. Wine Dataset Sampling (`wine_dataset_analysis.ipynb`)
- Loads the wine dataset from the `sklearn` library.
- Converts it into a Pandas DataFrame.
- Generates a random sample of size 50.
- Computes Z-critical value, margin of error, and confidence interval for alcohol content at a 95% confidence level.

## Installation & Requirements
Ensure you have the following dependencies installed:
```bash
pip install pandas numpy scipy scikit-learn
Usage
Navigate to the scripts directory and run the individual scripts. Example:

bash
Copy
Edit
cd scripts
python confidence_interval.py

Datasets
kerala.csv - Contains historical rainfall data for Kerala, India.
Wine dataset - Imported from sklearn.datasets.load_wine().

### Dataset Descriptions:
1. **Kerala Rainfall Dataset (`kerala.csv`)**  
   - Columns: Year, monthly rainfall data (Jan-Dec), annual rainfall, and flood indicator (YES/NO).
   - Purpose: Analyze rainfall trends and predict flood probabilities.

2. **Wine Dataset**  
   - Source: `sklearn.datasets.load_wine()`
   - Contains chemical composition of wines.
   - Used for statistical inference on alcohol content.

