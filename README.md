# Weather Analysis and Forecasting in Ho Chi Minh City

This project analyzes historical weather data for Ho Chi Minh City and explores relationships among weather variables. It also builds a linear regression model to predict the next day's average temperature from the current day's observations.

The analysis is documented in a Jupyter Notebook using an R kernel.

## Project Information

- **Team:** Group 4
- **Course:** DSR30301m
- **Semester:** Summer 2025 (SU25)

## Dataset

The notebook reads `dataexport_20250701T004455.csv`, which contains daily weather observations. The features used in the analysis include:

- Mean, maximum, and minimum temperature
- Total precipitation
- Maximum wind speed and wind gusts
- Dominant wind direction
- Observation date

The repository also includes `dataexport_20250701T004449.xlsx` as a spreadsheet data file.

## Workflow

The notebook walks through these steps:

1. Load the R packages used for data wrangling, visualization, and modeling.
2. Read the CSV file, assign descriptive column names, and parse the date column.
3. Explore temperature and precipitation trends and inspect correlations among numeric variables.
4. Create a target column containing the following day's mean temperature.
5. Split the data into training and test sets and train a linear regression model.
6. Evaluate predictions with regression metrics and compare predicted values with actual values in a plot.

## Requirements

- R 4.x
- Jupyter Notebook or JupyterLab with an R kernel (IRkernel)
- R packages: `tidyverse`, `lubridate`, `caret`, and `corrplot`

Install the packages in an R session if needed:

```r
install.packages(c("tidyverse", "lubridate", "caret", "corrplot"))
```

## Run the Notebook

1. Clone this repository.
2. Open `DuDoanThoiTiet.ipynb` in Jupyter Notebook or JupyterLab with an R kernel selected.
3. Make sure `dataexport_20250701T004455.csv` is available in the notebook's working directory. When launching Jupyter from the repository root, this is already the case.
4. Run the notebook cells from top to bottom.

## Project Structure

The directory tree is shown in a fenced code block to preserve its indentation on GitHub.

```text
DSR301-Asm/
├── DuDoanThoiTiet.ipynb          # Weather analysis and forecasting notebook (R)
├── dataexport_20250701T004449.xlsx # Spreadsheet dataset
├── dataexport_20250701T004455.csv  # Daily weather data used by the notebook
└── README.md                       # Project overview and instructions
```

## Notes

The notebook uses a randomly selected 80/20 train/test split with a fixed seed. Since the observations are time-ordered, a chronological split may be more suitable for a rigorous forecasting evaluation. The model and evaluation results depend on the supplied dataset and should be interpreted accordingly.
