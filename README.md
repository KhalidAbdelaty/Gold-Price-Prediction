# Gold Price Prediction Project

## Project Overview
In this project, I used historical data to predict gold prices. The dataset included variables such as the S&P 500 index (SPX), US Oil price (USO), Silver price (SLV), and EUR/USD exchange rate, along with the gold price (GLD).

## Steps Involved
1. **Data Understanding and Preprocessing**: Loaded the dataset, understood its structure, and checked for missing values.
2. **Exploratory Data Analysis**: Computed the pairwise correlation of the columns and visualized it using a heatmap. Also plotted a kernel density estimate (KDE) for the 'GLD' price.
3. **Model Building and Evaluation**: Split the data into training and test sets and chose a Random Forest Regressor for this regression problem. Trained the model, made predictions on the test data, and evaluated the model's performance using the R Squared Error.
4. **Visualizing the Results**: Plotted the actual vs predicted values of gold prices.

## Results
The model achieved a high level of accuracy, with an R Squared Error of 0.9890468369260285. The close alignment of the actual and predicted values on the plot indicated that the model's predictions were quite accurate.

## Libraries Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
