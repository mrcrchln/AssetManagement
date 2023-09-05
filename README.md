# AssetManagement
Asset Management 2023 - T4
Welcome to the GitHub repository for the Asset Management project for the year 2023 Term 4 (T4). This project involves the analysis of financial data and the creation of various portfolios to explore investment strategies. In this README, you will find instructions on how to set up and run the project, as well as an overview of the tasks and code snippets used in the analysis.

## Before you start, ensure you have the following dependencies installed:

- pandas
- numpy
- scipy
- matplotlib
- getFamaFrenchFactors
- statsmodels

You can install these dependencies using pip:
```
pip install pandas numpy scipy matplotlib getFamaFrenchFactors statsmodels
```

## Setup Data
To get started, you'll need access to the necessary data. We'll be using Google Colab for this project.
The first time you run the notebook you should access the following link: https://drive.google.com/drive/folders/1kKzxa0I3u4rPnCKiW2xB79Z0ls2k02Jh?usp=sharing and select the "Add Shortcut to Drive". This will add a shortcut to the datasets to your Google Drive.

The following cell will then mount the directory into Colab environment, so that it can be accessed as a local file.

```
from google.colab import drive
drive.mount('/content/drive')

# Set the file path
data_16 = "/content/drive/MyDrive/T4/AssetManagement/16_data.csv"
```
You can now simply import the data with pandas:
```
data = pd.read_csv(data_16)
```

