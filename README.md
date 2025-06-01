# Car Fines Prediction

This project aims to predict the most likely cars to commit traffic fines using GPU-accelerated data processing with cuDF and Dask cuDF. The model will be trained and evaluated using NVIDIA hardware to leverage the power of GPU parallelization.

## Project Structure
```
/car-fines-prediction
│
├── /data               # Folder for CSV or other data files
├── /notebooks          # Folder for Jupyter notebooks with analysis and training
├── /scripts            # Python scripts for data processing and modeling
├── /models             # Folder for saving trained models
├── /requirements.txt    # Project dependencies
└── /README.md           # Project explanation
```

## Installation
1. Clone the repository:
```
git clone https://github.com/KureishiDev/car-fines-prediction.git
```

2. Install dependencies:
```
pip install -r requirements.txt
```

## Usage
- Add your data files to the `/data` folder.
- Run the notebooks in `/notebooks` to train and evaluate the model.

## Dependencies
- cudf
- dask-cudf
- pandas
- scikit-learn
- numpy

## License
This project is licensed under the MIT License.

