# Python Data Analysis Exercises
![img_1.png](img_1.png)
<br>This repository contains a curated collection of **NumPy** and **pandas** exercises, plus a few **mini-projects** based on real-world style datasets.

The goal of this repo is twofold:

1. Practice core data analysis skills in Python (NumPy + pandas).
2. Showcase my coding style, workflow, and way of thinking about data problems.


NumPy exercises
Folder: numpy/
Focus: numerical computing, array manipulations, vectorization.

|file|description|
| -------- | -------- |
|01_basics.ipynb|Creation of arrays, basic operations, type conversions, simple statistics.
|02_indexing_slicing.ipynb|Indexing, slicing, boolean masks, modifying selected elements.
|03_reshaping_broadcasting.ipynb|Reshaping arrays, broadcasting rules, column-wise/row-wise operations.
|04_statistics.ipynb|Descriptive statistics, correlations, simple simulations (e.g. coin flips, normal distribution).
|05_numpy_100_selected.ipynb|A selection of tasks inspired by the famous “100 NumPy exercises”.

pandas exercises
Folder: pandas/
Focus: tabular data, cleaning, transformation, aggregation, time series.

| file                  |description|
|-----------------------| -------- |
|01_series_dataframe_basics.ipynb |Creating Series and DataFrame, loading CSV files, inspecting data, basic dtypes.
|02_indexing_filtering.ipynb|Selecting rows and columns (loc, iloc), conditional filtering, sorting.
|03_missing_values.ipynb|Detecting missing data, dropping vs imputing (dropna, fillna).
|04_groupby_aggregation.ipynb|Aggregations by groups (e.g. revenue per country/product), multiple aggregations with agg.                            
|05_merging_joining.ipynb|Joining multiple tables (customers, orders, etc.), combining datasets with merge and concat.
|06_reshaping_pivot.ipynb|Pivot tables, stack/unstack, melt for transforming wide/long data.
|07_time_series.ipynb|Working with dates, datetime index, filtering by date ranges, resampling daily/weekly/monthly.
|08_pandas_101_selected.ipynb|A set of more advanced exercises inspired by popular “pandas 101” lists:
duplicates, cumulative sums, percentage shares, custom functions in groupby.apply, etc.


Mini-projects
Folder: projects/
These folders contain slightly larger, more realistic analyses that combine multiple pandas/NumPy techniques.

## Repository structure
```text
python-data-analysis-exercises/
│
├─ numpy/
│   ├─ 01_basics.ipynb
│   ├─ 02_indexing_slicing.ipynb
│   ├─ 03_reshaping_broadcasting.ipynb
│   ├─ 04_statistics.ipynb              (planned)
│   └─ 05_numpy_100_selected.ipynb      (planned)
│
├─ pandas/
│   ├─ 01_series_dataframe_basics.ipynb (planned)
│   ├─ 02_indexing_filtering.ipynb      (planned)
│   ├─ 03_missing_values.ipynb          (planned)
│   ├─ 04_groupby_aggregation.ipynb     (planned)
│   ├─ 05_merging_joining.ipynb         (planned)
│   ├─ 06_reshaping_pivot.ipynb         (planned)
│   ├─ 07_time_series.ipynb             (planned)
│   └─ 08_pandas_101_selected.ipynb     (planned)
│
├─ projects/
│   ├─ 01_bike_sharing_analysis/        (planned)
│   ├─ 02_sales_analysis/               (planned)
│   └─ 03_custom_project/               (planned)
│
└─ README.md
```

How to run the notebooks

1. Clone this repository
```text
git clone https://github.com/pszul/python-data-analysis-exercises
cd python-data-analysis-exercises
```
2. Install dependencies
```text
pip install -r requirements.txt
```
3. Start Jupyter
```text
jupyter notebook
```

## Technologies used
- Python
- NumPy
- pandas
- Jupyter Notebook
- matplotlib
- seaborn

## Notes

- All datasets in this repository are either synthetic, simplified, or publicly available.
- This repo is work-in-progress – I plan to keep adding more exercises and projects over time.
- Feedback and suggestions are welcome: feel free to open an issue or contact me.
