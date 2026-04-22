# District-Level Crop Yield Prediction in India Using APY Statistics

## Project aim
This project investigates whether tree-based machine-learning models can predict district-level crop yields across India using only Area, Production and Yield (APY) administrative statistics.

## Research question
To what extent can tree-based machine-learning models trained solely on APY statistics accurately predict district-level crop yields in India, and how do they compare with a linear regression baseline?

## Data used
The project uses the official APY dataset for India, containing district, state, crop, season, crop year, area, production and yield information.

## Repository structure
- `data/raw/` raw input data
- `24085801_crop_yield_analysis.ipynb` Jupyter notebook used for analysis
- `District-Level Crop Yield Prediction for India Using Machine Learning.pdf` presentation slides
- `requirement.txt` libraries needs to used
- `24085801 crop_yield_analysis.pdf` final report PDF

## Inputs
- Raw APY CSV file

## Outputs
- Cleaned modelling dataset
- Exploratory plots
- Model performance metrics
- Feature-importance plots
- Final report

## Methods
- Ridge regression
- Random Forest regressor
- Histogram-based Gradient Boosting regressor
- Regularised Random Forest
- Crop-specific Random Forest for high-yield crops

## How to run
1. Clone the repository
2. Install dependencies:
   `pip install -r requirements.txt`
3. Open and run `notebooks/crop_yield_analysis.ipynb`

## Notes
The project uses a temporal train-validation-test split based on crop year.
