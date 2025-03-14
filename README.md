# Hyperspectral_data_mycotoxin_level_prediction

## Folder Contents
- **requirements.txt**: All ```pip```-installable libraries used for this project are listed here.
- **spectral_data.csv**: CSV file containing training data.
- **test.csv**: CSV file containing test data used for inference in ```Prediction.ipynb```
- **prepross.ipynb**: This is the file contains all Data preprocessing steps to clean data.
- **train.ipynb** : This file contains code realted to Model training, evaluation and model selction .
- **Prediction.ipynb**: This file is used for prediction from trained model (xgb.pkl).
- **xgb_model.pkl**: Binary file storing trained model.
- **pca.pkl**: Binary file to transform data using pca.
- **x_scaler.pkl**: Binary file storing scaling parameter (satndar scaler).

## Prerequisites
Run the following command in the terminal after navigating to the project's directory:
```
pip install -r requirements.txt
```

