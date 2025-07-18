# MSCS_634_Lab_2

## Purpose
Using the Wine dataset, this lab shows how well K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) do in classification. The main aim of this lab is to assess the effects of varying k and radius values on model.

## Key Insights
- KNN performed well with highest accuracy around k=5 or k=11.
- RNN showed unstable results depending on the radius size, and failed to classify some test samples.
- KNN is more reliable unless there is a clear rationale for using radius-based neighborhood.

## Challenges Faced
- RadiusNeighborsClassifier does not return predictions for all test samples, especially with small radii which required filtering invalid predictions.
- It was difficult to choose radius values since missing predictions occurred when radii were too small.

## How to Run
Clone the repo, open the Jupyter Notebook, and run all cells.
