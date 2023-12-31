# AssetManagement
Asset Management 2023 - T4
Welcome to the GitHub repository for the Asset Management project for the year 2023 Term 4 (T4). This project involves the analysis of financial data and the creation of various portfolios to explore investment strategies. In this README, you will find instructions on how to set up and run the project.

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

## Data Source
The data for this project is sourced from the "Tickers" file, which specifies the tickers of the 50 stocks required for your assignment number. The data includes monthly Book-to-Market data and monthly prices for these stocks. The file path to the data is provided in the setup section of this README.

Please ensure you have access to the necessary data file to run the project successfully. You can adjust the file path as needed to match your data location.

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

## License
This project is licensed under the MIT License - see the LICENSE file for details.
