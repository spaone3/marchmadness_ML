# March Madness Machine Learning Project

## 🏀 Overview
A machine learning pipeline for predicting NCAA March Madness tournament outcomes. This project includes data preprocessing, feature engineering, and modeling notebooks.

## 🛠️ Setup

### Prerequisites
- Python 3.8+
- pip package manager

### 1. Installation
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt


## 📂 Data Acquisition

### 2. Download Tournament Data

Download the dataset from Kaggle's [March Machine Learning Mania 2025](https://www.kaggle.com/competitions/march-machine-learning-mania-2025/data):

- Place all downloaded files in the `data/` directory.

Save all files to:
    ```bash
    /data/
    ```

### 3. Download Massey Ratings

To perform clustering, you'll need Massey Ratings data:

- Go to [https://masseyratings.com/cb/ncaa-d1/ratings](https://masseyratings.com/cb/ncaa-d1/ratings)
- Download ratings individually by year.
- Place them in the following directories:
    ```bash
    data/MMasseyRatings/mens/
    data/MMasseyRatings/womens/
    ```

## 🚀 Usage Pipeline

### Preprocessing
Run the Jupyter notebook:
    ```bash
    z_finalproj/preprocessdata.ipynb
    ```

### Model Training & Analysis
Run the notebooks in your perferred order


## Folder Hierarchy
.
├── data/                   # Raw data storage
│   ├── MMasseyRatings/     # Massey ratings by gender
│   │   ├── mens/           # Men's ratings
│   │   └── womens/         # Women's ratings
│   └── [kaggle_data]       # Competition files
├── notebooks/              # Analysis notebooks
│   ├── preprocessdata.ipynb
│   └── [model_notebooks]
├── requirements.txt        # Python dependencies
└── README.md


