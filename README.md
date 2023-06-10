## 1-Gaussian Process Modeling for Energy Consumption Data
This repository contains code for modeling energy consumption data using Gaussian processes. The data is provided in the EnergyConsumptionData.xlsx file, which includes 500 points of input-output pairs.

### Code Description
The gaussian_process.ipynb file in this repository implements the Gaussian Process algorithm for modeling the provided data. It performs the following tasks:

1. Reads the data from the EnergyConsumptionData.xlsx file.
2. Plots the data to identify its main properties, such as frequency and amplitude.
3. Uses the Gaussian process method with a specific kernel to model the data.
4. Calculates the expected quadratic error between the model and raw data.
5. Determines the expected value of y for a given x value.

The code utilizes the NumPy, Pandas, Matplotlib, and Openpyxl libraries for data manipulation, visualization, and mathematical computations.

### Usage
To use the code, follow these steps:

1. Ensure that the required libraries mentioned above are installed in your Python environment.
2. Clone the repository using the provided Git repository link.
3. Open the gaussian_process.py file and modify the parameters of the GaussianProcess class as needed.
4. Run the script to obtain the desired results.

### Results
The code generates plots that show the Gaussian process mean function and compares it with the true values from the data. It also provides the expected quadratic error between the model and raw data and calculates the expected value of y for a specific x value.

### Acknowledgments
This code was developed as part of a data modeling assessment for the store assistant vacancy at Pandora. It demonstrates the application of Gaussian processes for energy consumption data modeling.

### Requirments
To run the code, you will need the following dependencies and resources:
``` 
numpy==1.22.4
scikit-learn==1.2.2
pandas==1.5.3
matplotlib==3.7.1
openpyxl==3.0.10

``` 
