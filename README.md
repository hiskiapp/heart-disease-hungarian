# Hungarian Heart Disease Classification
This project is a simple web app to classify heart disease using the Hungarian Heart Disease dataset.

## Files
- `main.py`: This is the main script that runs the Streamlit app for heart disease classification.
- `model/knn.joblib`: This is the trained K-Nearest Neighbors model used for prediction.
- `model/knn.pkl`: This is the pickled version of the trained model.
- `data/template.csv`: This is a template CSV file for batch prediction.
- `requirements.txt`: This file lists all the Python dependencies required for this project.

## Setup
1. Clone the repository.
2. Install the dependencies using pip:
```bash
pip install -r requirements.txt
```
3. Run the Streamlit app:
```bash
streamlit run main.py
```

## Usage
The app has two tabs: Single Prediction and Batch Prediction.
- In the Single Prediction tab, enter the values to predict heart disease.
- In the Batch Prediction tab, upload a CSV file to predict heart disease for multiple inputs.

## Links
- [Datasets](https://archive.ics.uci.edu/dataset/45/heart+disease)
- [Deepnote Notebook](https://deepnote.com/@hiskia/Heart-Disease-BK-4e521e1d-c937-48e4-b4ad-584bf559f6c4)
