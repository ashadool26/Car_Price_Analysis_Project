# Car Resale Price Analysis & Visualization System

A data analysis project that explores used-car resale pricing patterns and presents insights through feature engineering, exploratory analysis, and visualizations.

## Project Overview
This project analyzes historical car sales data to answer practical dealership questions such as:
- Which brands tend to have higher resale value?
- How does vehicle age impact price?
- How can cars be grouped into pricing segments for business decisions?

The analysis is implemented in a Jupyter Notebook and combines:
- **Python fundamentals and OOP** (a `CarSale` class for simple vehicle modeling)
- **Pandas** for cleaning, transformation, and descriptive analytics
- **NumPy** for feature engineering and segmentation logic
- **Matplotlib / Seaborn** for professional exploratory visualizations

## Repository Structure
- `Car_Price_Analysis_Project (1).ipynb` — main notebook containing the full workflow
- `README.md` — project documentation

## Workflow Summary
1. Load and inspect the dataset (`daTA.csv` in the notebook).
2. Perform schema and quality checks (`info`, null-value handling).
3. Build an OOP example (`CarSale`) to demonstrate domain-oriented modeling.
4. Engineer features:
   - `Car_Age = current_year - Year`
   - Price-based market segment labels (`Low`, `Medium`, `High`) using NumPy.
5. Generate descriptive statistics and brand-level price comparisons.
6. Visualize key patterns with:
   - Price distribution histogram
   - Average price by brand bar chart
   - Price-by-segment box plot
   - Price vs. age scatter plot with segment coloring

## Key Insights Produced
- Distribution and spread of resale prices
- Brand-wise average price differences
- Relationship between car age and resale price
- Segment-level pricing behavior for inventory strategy

## Requirements
Install dependencies before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

## How to Run
1. Ensure your dataset is available as `daTA.csv` (or update the file path in the notebook).
2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open `Car_Price_Analysis_Project (1).ipynb` and run all cells in order.

## Potential Enhancements
- Add model-based price prediction (e.g., regression pipelines)
- Incorporate outlier handling and robust statistical checks
- Convert notebook logic into reusable Python modules
- Add automated tests and data validation checks

## Author
Car Price Analysis Project
