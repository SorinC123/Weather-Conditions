# Weather Conditions and Climate Change

## Project Summary
This project assesses the tools available to categorize and predict the weather in mainland Europe using data collected by the European Climate Assessment & Data Set project. The study aims to explore the prediction accuracy of different
algorithms: K-nearest neighbors, Decision Tree, and Artificial Neural Networks. Gradient Descent algorithm was used for optimization.

## Key Questions
- Can machine learning algorithms effectively predict future weather conditions?

- Which machine learning algorithm can be considered the definitive best choice for weather prediction?

- Does prediction accuracy vary depending on the algorithm used and the geographic location?

## Data Overview
The data sets used for this project include:

- weather observations from 18 different weather stations across Europe.
  
- data ranging from 1960 to 2022.
  
- recordings for almost every day with values such as temperature, wind speed, snow, global radiation, and more. 

The data was gathered from various sources, including hurricane predictions from the U.S. National Oceanic and Atmospheric Administration (NOAA), typhoon data from the Japan Meteorological Agency (JMA), global temperature records, and numerous other data sets.


## Folders
The folder structure and their contents are outlined below:
- 01 Data: Data sourced from the European Climate Assessment & Data Set project in CSV/pickle format (unscaled and scaled).
The scaled data could not be uploaded due to its file size.
- 02 Scripts: Python code used in the analysis, executed using Jupyter Notebooks.

## Coding Overview
Code was written in Python and executed in Jupyter notebooks.
#### The following libraries were utilized:
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations and array handling.
- OS: For interacting with the operating system, including file and directory operations.
- Matplotlib.pyplot: For creating static, interactive, and animated visualizations.
- Seaborn: For statistical data visualization and creating graphics.
- Scikit-learn (sklearn): For implementing KNN, Decision Tree, and ANN algorithms; also, for optimization using the Gradient Descent algorithm.

