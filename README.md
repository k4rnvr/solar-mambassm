# Solar Power Forecasting

This project demonstrates how to use Mamba-SSM to forecast solar power generation based on historical data. It combines a set of Parquet files with a Jupyter Notebook that processes, analyzes, and models the data.

## Files

- `solarPV_MambaSSM.ipynb` – Main notebook with EDA, model training, and evaluation

## Dataset

The dataset includeswas taken from NIST Campus Photovoltaic (PV) Arrays and Weather Station Data Sets
One-minute averaged values for 2017 for three grid-connected photovoltaic arrays on the NIST campus in Gaithersburg, Maryland USA.
Link: https://catalog.data.gov/dataset/nist-campus-photovoltaic-pv-arrays-and-weather-station-data-sets-05b4d
All files were converted into Apache Parquet format for 12 months for optimized performance
Link: https://drive.google.com/file/d/1JvN0-bv7frRf8BAxVrmtJoYV-vzjjt0d/view?usp=sharing

*Note: You may need to manually upload the dataset or use `gdown` to download it. The Dataset is also linked inside the .ipynb file.*
