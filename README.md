# Ji_Wu_PS1

# **King County House Price Analysis**

## **📌 Project Overview**
This project analyzes **King County, USA** house price data to explore key factors influencing property prices using data analytics and machine learning.

## **📊 Dataset Overview**
- **Source**: King County real estate transactions
- **Total records**: 21,614
- **Format**: CSV
- **Key Features**:
  - `id` - Unique house identifier
  - `date` - Sale date
  - `price` - Sale price (Target variable)
  - `bedrooms` - Number of bedrooms
  - `bathrooms` - Number of bathrooms
  - `sqft_living` - Square footage of living space
  - `floors` - Number of floors
  - `waterfront` - Whether the property has a waterfront view (0=No, 1=Yes)
  - `zipcode` - Postal code
  - `lat`, `long` - Geographic coordinates
  
## **📈 Exploratory Data Analysis (EDA)**
### **Objectives**
- **Check data integrity** (missing values, data types, etc.)
- **Visualize price distribution and key influencing factors**
- **Analyze correlations between price and features**
- **Clean data and save it as `kc_house_cleaned.csv` for further analysis**

### **Running the EDA Notebook**
1. Open and run `notebooks/eda_kc_house.ipynb` to explore the dataset.
2. Run `src/data_preprocessing.py` to clean and preprocess the data.

## **📂 Project Structure**
```
kc_house_analysis/
│── data/
│   │── kc_house_data.csv       # Raw dataset
│   │── kc_house_cleaned.csv    # Preprocessed dataset
│── notebooks/
│   │── eda_kc_house.ipynb      # EDA Jupyter Notebook
│── src/
│   │── data_preprocessing.py   # Data cleaning & preprocessing script
│   │── feature_engineering.py  # Feature engineering
│   │── model_training.py       # Train machine learning models
│── reports/
│   │── eda_summary.pdf         # Summary of EDA results
│── README.md                   # Project & dataset documentation
```

## **📚 Future Enhancements**
- **Develop machine learning models to predict house prices**
- **Incorporate spatial analysis using geographic data**
- **Explore the impact of AI-generated property descriptions on price predictions**

