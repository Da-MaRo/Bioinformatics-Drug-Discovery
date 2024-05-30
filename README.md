# Bioinformatics-Drug-Discovery

## Overview
This repository contains Jupyter notebooks that serve as a tutorial based on the content presented by Chanin Nantasenamat, also known as the 'Data Professor', on the YouTube channel. The tutorials focus on bioinformatics and drug discovery, specifically exploring the use of machine learning techniques to analyze data from the ChEMBL database.

## Data Retrieval and Preprocessing
The notebooks demonstrate how to access the ChEMBL database to retrieve information on inhibitors of HSC70. The retrieved data is then subjected to preprocessing steps, including cleaning and feature engineering using PaDEL descriptors.

## Model Development
An initial RandomForest regression model is constructed using the preprocessed data. The notebook walks through the process of training and evaluating this model.

## Model Screening and Evaluation
The final stage involves model screening, where various regression algorithms are applied and compared. The notebooks highlight the ExtratreesRegressor as the standout model based on performance metrics.

## Dependencies
To run these notebooks, ensure you have the necessary dependencies installed. This may include Python libraries such as pandas, numpy, scikit-learn, and others. Additionally, access to the ChEMBL database and PaDEL descriptor tools may be required.

## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Open and run the Jupyter notebooks in the specified order to follow the tutorial and reproduce the analysis.

## Credits
- **Chanin Nantasenamat ('Data Professor')**: For providing the educational content and inspiration for this tutorial.
- **ChEMBL Database**: For providing the valuable data on inhibitors of HSC70.
- **PaDEL Descriptor**: For the tools used in feature engineering and descriptor generation.
- **Scikit-learn**: For providing the machine learning algorithms and tools used in model development and evaluation.
