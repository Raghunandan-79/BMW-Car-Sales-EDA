# BMW Car Sales EDA

An exploratory data analysis project that visualizes and analyzes BMW car sales data across different models, regions, fuel types, and time periods.

## 📊 Project Overview

This project performs comprehensive exploratory data analysis on BMW car sales data, generating insightful visualizations to understand sales trends, model performance, fuel type preferences, and revenue patterns over time.

## 📁 Dataset

The dataset (`BMW_sales.csv`) contains BMW car sales information with the following attributes:

- **Model**: BMW model name (e.g., 3 Series, 5 Series, X3, i8, M5, etc.)
- **Year**: Sales year (2012-2024)
- **Region**: Sales region (Asia, North America, Europe, Middle East, South America, Africa)
- **Color**: Vehicle color
- **Fuel_Type**: Fuel type (Petrol, Diesel, Hybrid, Electric)
- **Transmission**: Transmission type (Manual, Automatic)
- **Engine_Size_L**: Engine size in liters
- **Mileage_KM**: Vehicle mileage in kilometers
- **Price_USD**: Price in USD
- **Sales_Volume**: Number of units sold
- **Sales_Classification**: Sales classification (High/Low)

## 🔍 Analysis & Visualizations

The notebook includes the following analyses and visualizations:

1. **Sales Volume by Year** - Line chart showing total BMW sales volume trends over time
2. **Sales by Model** - Bar chart displaying total sales volume for each BMW model
3. **Sales by Fuel Type** - Four subplots showing sales trends for:
   - Petrol models
   - Diesel models
   - Hybrid models
   - Electric models
4. **High vs Low Sales Classification** - Pie chart showing the distribution of high and low sales classifications
5. **Revenue by Year** - Line chart displaying total revenue trends over time (calculated as Price × Sales Volume)

## 🛠️ Requirements

To run this project, you'll need:

- Python 3.x
- pandas
- matplotlib

Install the required packages:

```bash
pip install pandas matplotlib
```

## 🚀 Usage

1. Clone or download this repository
2. Ensure the `BMW_sales.csv` file is in the same directory as the notebook
3. Open `bmw_sales_data_visualization.ipynb` in Jupyter Notebook or JupyterLab
4. Run all cells to execute the analysis and generate visualizations

## 📈 Key Insights

The analysis provides insights into:
- Sales trends and patterns over the years
- Most popular BMW models
- Fuel type preferences and market shifts
- Revenue generation patterns
- Sales performance classifications

## 📂 Project Structure

```
BMW-Car-Sales-EDA/
├── bmw_sales_data_visualization.ipynb  # Main analysis notebook
├── BMW_sales.csv                        # Dataset
└── README.md                            # Project documentation
```

## 📝 Data Processing

The notebook includes data cleaning steps:
- Converting columns to appropriate data types (numeric)
- Handling missing values by dropping rows with null values
- Creating derived columns (e.g., Revenue = Price_USD × Sales_Volume)

## 📊 Visualizations

All visualizations are generated using matplotlib with:
- Custom color schemes for different chart types
- Proper labeling and legends
- Grid lines for better readability
- Appropriate figure sizes for clarity

---

**Note**: This project is for educational and analytical purposes, providing insights into BMW car sales patterns and trends.
