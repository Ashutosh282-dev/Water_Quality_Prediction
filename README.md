# Water Quality Prediction Project

## Project Overview
This project focuses on predicting water potability using machine learning techniques. The goal is to analyze water quality parameters and determine if the water is safe for consumption.

## Project Structure
```
water_quality_prediction/
├── data/                   # Raw and processed data
├── notebooks/              # Jupyter notebooks for analysis
│   └── water_quality_prediction_week1.ipynb  # Week 1 analysis
├── models/                 # Saved models
├── src/                    # Source code
└── README.md              # Project documentation
```

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd water_quality_prediction
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Then open `notebooks/water_quality_prediction_week1.ipynb`

## Week 1 Tasks
- [x] Project setup and environment configuration
- [x] Data loading and initial exploration
- [x] Data preprocessing and cleaning
- [x] Exploratory Data Analysis (EDA)
- [x] Data preparation for modeling

## Next Steps
- Upload your water quality dataset to the `data/` directory
- Update the file path in the notebook
- Run the notebook cells sequentially to perform the analysis

## Dataset Information
Please ensure your dataset includes water quality parameters such as:
- pH value
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity
- Potability (target variable)

## License
This project is part of the AICTE Internship Program.
