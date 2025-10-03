# -ML-File-Type-Classification-System
Machine learning model that identifies file types (JPEG, PNG, PDF) by analyzing file headers using Random Forest.

## Features
- Classifies files using first 10 bytes (headers)
- Random Forest algorithm with high accuracy
- Interactive testing in Jupyter notebook
- Train model directly from your dataset

## Tech Stack
- Python, Scikit-learn, Random Forest
- NumPy, Pandas, Matplotlib
- Jupyter Notebook

## Usage
1. Organize files in `dataset/jpeg/`, `dataset/png/`, `dataset/pdf/`
2. Run the notebook to train model
3. Use `predict_file_type("your_file")` for predictions

## Project Structure
```
file-type-classifier/
├── file_type_classification.ipynb
├── requirements.txt
└── dataset/
    ├── jpeg/
    ├── png/
    └── pdf/
```
