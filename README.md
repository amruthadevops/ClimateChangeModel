
# 🌍 Climate Change Modeling with Machine Learning

This repository contains an end-to-end data science project focused on modeling and analyzing climate change indicators using real-world climate data and user sentiment. The project combines Natural Language Processing (NLP), exploratory data analysis, machine learning, and geospatial visualizations to assess and project climate change impacts.


##  📌  Objectives

- Predict and analyze climate change indicators such as temperature anomalies, CO₂ emissions, and extreme weather trends.
- Analyze public sentiment around climate change using Facebook comments from NASA's climate page.
- Apply machine learning to forecast climate metrics and visualize their progression over time and geography.
##  📊  Tech Stack

- **Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `folium`, `geopandas`, `tqdm`
- **ML Models**: Random Forest, XGBoost, LSTM (future scope)
- **Development Tools**: Jupyter Notebook, VS Code

##  🧠  Features

1. **Exploratory Data Analysis (EDA)**:
- CO₂ emission patterns across time and location
- Sentiment trends on climate change topics
- Outlier detection, skewness handling, and missing value imputation


3. **Sentiment Analysis (NLP)**
- Analyze over 500 user comments from NASA’s Facebook Climate Change page (2020–2023).
- Perform trend analysis and topic modeling using NLP.
- Data privacy is preserved using SHA-256 hashing for user anonymity.

4. **Climate Data Modeling**
- Dataset includes climate metrics such as CO₂ levels, solar radiation, temperature, sea level, and more.
- Feature engineering and preprocessing (normalization, encoding, handling outliers and missing values).
- Advanced time-series visualizations by week, year, and geographical coordinates.

5. **Machine Learning**
- Trained multiple models: Random Forest, Gradient Boosting, Neural Networks, and LSTM.
- Model evaluation using MAE, MSE, R², and cross-validation.
- Future forecasting and scenario simulation.
##   🗂️  Project Structure

```bash
├── main.ipynb              # Main notebook for climate modeling
├── data/                   # Raw and cleaned datasets
└── README.md               # Project documentation
```
## Set Up Environment:

- Recommended: Create a virtual environment

```
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate
    
```
- Install required packages:
``` 
    pip install -r requirements.txt
```
- Run the Notebook:
```
    Open main.ipynb in Jupyter Notebook and run the cells step-by-step.
```
## 📌 Key Insights

- Public sentiment shows increasing concern and awareness about climate change.

- High emissions correlate with specific aerosol and cloud indicators.

- Significant seasonal and geographical emission trends were discovered.
## 📈 Future Improvements

- Integrate real-time data updates using APIs.

- Deploy model as a Flask/Django web app.

- Collaborate with domain experts for deeper scientific validation.
## 🙏 Acknowledgements

- NASA Climate Change Facebook for social sentiment data

- NOAA, IPCC, and Kaggle for climate datasets

- BriantOliveira for reference EDA structure

## 📬 Contact

Amrutha C

GitHub: @amruthadevops

