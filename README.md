# Credit Fraud Detection

A credit card fraud detection model built with LightGBM and CUDA for fast GPU-accelerated training and inference. The project includes a Streamlit frontend for interactive fraud prediction.

## Tech Stack

- Python
- LightGBM
- CUDA
- Streamlit
- Pandas / NumPy

## Features

- GPU-accelerated LightGBM model
- Credit card fraud prediction
- Interactive Streamlit inference interface
- Fast inference workflow

## Run the Frontend

Install the required dependencies, then run:
- python -m streamlit run ModelInference.py

The Streamlit app will open in your browser.

## Project Structure

├── dataset.csv

├── Fraud_Detection_Model.jb

├── label_encoder.jb

├── Model Inference.py

├── ModelTraining.ipynb

├── requirements.txt

└── README.md


## Note

CUDA-compatible hardware and drivers are required for GPU-accelerated LightGBM.
