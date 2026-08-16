# Page View Time Series Visualizer

A data analysis project built as part of freeCodeCamp's **Data Analysis with Python** certification. This project visualizes daily page view data from the freeCodeCamp forum (2016-2019) to uncover trends and seasonal patterns.

## What it does

- Imports and cleans daily page view data, filtering out the top and bottom 2.5% of values as outliers
- **Line Plot** (`draw_line_plot`) — shows daily page views across the full date range
- **Bar Plot** (`draw_bar_plot`) — shows average page views grouped by month, split by year, to compare growth and seasonal patterns
- **Box Plots** (`draw_box_plot`) — two side-by-side plots: one showing the year-over-year trend, one showing month-to-month seasonality

## Tech used

- Python
- Pandas
- Matplotlib
- Seaborn

## Key concepts practiced

- Setting a datetime column as a DataFrame index with `parse_dates`
- Filtering outliers using percentiles
- Reshaping grouped data with `groupby` and `unstack`
- Multi-panel figures with `plt.subplots`
- Formatting dates into readable labels with `.strftime`
- Enforcing custom category order (calendar order vs. alphabetical) in plots

## Files

- `time_series_visualizer.py` — main project code
- `main.py` — runs the functions and the test suite
- `test_module.py` — unit tests provided by freeCodeCamp
- `fcc-forum-pageviews.csv` — dataset

## Run it

```
python main.py
```
