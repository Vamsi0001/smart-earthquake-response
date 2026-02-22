# Smart Earthquake Response System

## Overview
This project implements machine learning and spatial statistics techniques for earthquake clustering, prediction, and response analysis using Indonesia earthquake data.

## Features
- **Spatial Clustering**: DBSCAN algorithm for earthquake epicenter clustering
- **Spatial Autocorrelation**: Moran's I test for spatial correlation analysis
- **Geographically Weighted Regression (GWR)**: Local regression modeling for spatial variation
- **Kriging Interpolation**: Spatial interpolation of earthquake parameters
- **Neural Network Models**: Deep learning models for earthquake forecasting
- **Time Series Analysis**: Earthquake frequency and magnitude forecasting

## Project Structure
```
smart-earthquake-response/
├── notebooks/
│   ├── Indonesia-3-checkpoint.ipynb       # Main ML and time-series analysis
│   ├── DBMS_finalsem.ipynb               # Database management and analysis
│   └── evalaluation4_bl.sc.p2cse25025-1.ipynb  # Spatial analysis and evaluation
├── data/
│   └── earthquake_cleaned.csv            # Cleaned Indonesia earthquake dataset
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset
- **File**: `earthquake_cleaned.csv`
- **Source**: Indonesia earthquake records
- **Contains**: Latitude, longitude, magnitude, depth, and temporal data

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Vamsi0001/smart-earthquake-response.git
cd smart-earthquake-response
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Open Jupyter Notebook and run the notebooks in the following order:
```bash
jupyter notebook
```

1. **Indonesia-3-checkpoint.ipynb** - Main analysis with ML models
2. **DBMS_finalsem.ipynb** - Database and management aspects
3. **evalaluation4_bl.sc.p2cse25025-1.ipynb** - Comprehensive evaluation

## Key Methods

### DBSCAN Clustering
Clusters earthquake epicenters based on density for identifying seismic zones.

### Moran's I Test
Measures spatial autocorrelation in earthquake occurrence patterns.

### Geographically Weighted Regression
Models spatial variation in earthquake parameters across regions.

### Kriging Interpolation
Predicts earthquake parameters at unsampled locations using spatial correlation.

### Neural Networks
Deep learning models for earthquake magnitude and frequency prediction.

## Dependencies
- Python 3.7+
- numpy
- pandas
- scikit-learn
- geopandas
- matplotlib
- seaborn
- scipy
- jupyter

## Author
Vamsi0001

## License
MIT License

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
