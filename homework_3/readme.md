# Homework 3


## Running the Code
To run the source code, go to `Homework_3.ipynb` and run all cells. Make sure to have all the required packages installed.

The script loads NYC taxi datasets from S3, standardizes and cleans records, then perfroms analyses and trains a Gradient Boosted Tree regression model. Outputs are saved to S3.


## Output Paths
Results are written to `s3://nky8459-de300/nyc-taxi-assignment/`, including:
- Train/test prediction tables in Parquet format
- Scatterplot of predicted vs. actual fare amount