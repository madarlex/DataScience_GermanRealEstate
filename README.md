# German Housing Price Analysis

This project analyzes housing prices in Germany using a dataset of real estate listings and a Jupyter notebook for data cleaning, feature engineering, and regression modeling.

## Project Structure

- `housing_price_ge19.csv`  
  The main dataset containing German housing listings with features such as price, lot size, age, land value, construction type, heating, and more.

- `housing-in-germany.ipynb`  
  Jupyter notebook containing all data analysis steps, including:
  - Data import and initial exploration
  - Data cleaning (handling missing values, encoding categorical variables)
  - Feature selection and outlier removal
  - Data standardization and PCA
  - Regression modeling and evaluation
  - Visualization of results

## Getting Started

1. **Install requirements**  
   Make sure you have Python 3 and the following packages installed:
   - numpy
   - pandas
   - scikit-learn
   - matplotlib
   - seaborn
   - jupyter

   You can install them using pip:
   ```sh
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter
   ```

2. **Open the notebook**  
   Launch Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
   Then open `housing-in-germany.ipynb`.

3. **Run the analysis**  
   Execute the cells in order to reproduce the data cleaning, modeling, and visualization steps.

## Data

The dataset (`housing_price_ge19.csv`) contains the following columns:
- Number (ID)
- Price
- Lot_Size
- Waterfront
- Age
- Land_Value
- New_Construct
- Central_Air
- Fuel_Type
- Heat_Type
- Sewer_Type
- Living_Area
- Pct_College
- Bedrooms
- Fireplaces
- Bathrooms
- Rooms

## Results

The notebook provides:
- Descriptive statistics and visualizations
- Correlation analysis
- Feature selection and dimensionality reduction (PCA)
- Regression modeling (Linear Regression)
- Model evaluation metrics (R², RMSE)
- Plots comparing predicted and actual prices

## License

This project is for educational and research purposes.

---
