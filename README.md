# Pandas Analyzer & Data Visualization

A menu-driven Python application for exploring, cleaning, analyzing, and visualizing CSV datasets using Pandas, NumPy, Matplotlib, and Seaborn.

This project provides a simple way to perform common data analysis tasks through an interactive console menu, without requiring users to write separate code for every operation.

## Project Overview

The Pandas Analyzer is designed to work with different CSV datasets. Users can load a dataset, inspect its structure, clean missing values, perform mathematical and statistical operations, and create visualizations to better understand their data.

The project demonstrates practical use of Python libraries for data analysis, data manipulation, and visualization.

## Features

### 1. Load Dataset
- Load CSV files from a specified path.
- Display the number of rows and columns.
- Automatically identify common date and numeric columns.

### 2. Explore Data
- Display the first and last five rows.
- View column names and data types.
- Check dataset shape and information.
- Generate descriptive summaries.
- Identify missing values.

### 3. Clean Data
- Display missing values.
- Fill numeric missing values using column means.
- Replace missing values with a custom value.
- Remove rows containing missing values.
- Remove duplicate records.
- Convert columns to numeric or datetime formats.

### 4. NumPy Operations
- Display numeric arrays.
- View array dimensions, shape, size, and data type.
- Perform indexing and slicing.
- Reshape arrays.
- Calculate element-wise squares.

### 5. Mathematical Operations
- Addition, subtraction, multiplication, and division.
- Square and square root.
- Absolute values.
- Basic validation for mathematical operations.

### 6. Search, Sort and Filter
- Search for text or values.
- Sort dataset records.
- Filter using exact values.
- Filter numeric columns within a range.

### 7. DataFrame Operations
- Combine datasets using concatenation.
- Merge DataFrames using a common key.
- Join DataFrames by index.
- Split a dataset into separate CSV files.
- Re-index the dataset.

### 8. Statistical Analysis
- Sum, mean, median, minimum, and maximum.
- Count and standard deviation.
- Variance and percentiles.
- Correlation analysis.
- Group-based aggregation.
- Pivot table generation.

### 9. Data Visualization
Create different charts using Matplotlib and Seaborn:

- Bar chart
- Line chart
- Scatter plot
- Pie chart
- Histogram
- Stack plot
- Correlation heatmap
- Box plot
- Multiple subplots

Charts can be customized with labels, colors, markers, legends, transparency, and line styles.

### 10. Export Results
- Export the processed dataset to CSV.
- Save generated visualizations as PNG or JPG.
- Export an analysis summary as a text file.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading, cleaning, and manipulation |
| NumPy | Numerical and array operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts and heatmaps |

## Project Structure

```text
sales_data_analyzer/
│
├── sales_data_analyzer.py
├── Chocolate_sales.csv
├── README.md
│
└── outputs/
    ├── analysis_summary.txt
    ├── pivot_table.csv
    └── visualizations/
        └── chart.png
```

The `outputs` and `visualizations` folders are created automatically when the program runs.

## Installation

### 1. Install Python

Install Python 3.10 or later from the official website:

https://www.python.org/downloads/

### 2. Install Required Libraries

Open the terminal or command prompt and run:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run

1. Download or clone the project.
2. Place your CSV dataset in the project folder.
3. Open the project folder in your terminal.
4. Run the following command:

```bash
python sales_data_analyzer.py
```

5. Follow the menu options displayed in the terminal.
6. Select the dataset path when prompted, or press Enter to load the default `Chocolate_sales.csv` file.

## Dataset Compatibility

The analyzer can load different CSV datasets. Most general exploration, cleaning, filtering, and statistical operations work with suitable columns in any CSV file.

Some operations require specific data types:

- Mathematical operations require numeric columns.
- Numeric range filtering requires a numeric column.
- Date analysis works best with properly formatted date columns.
- Pivot tables require a numeric values column.
- Charts require suitable categorical or numeric data.

The program does not require every dataset to contain the same column names.

## Output Files

Generated files are saved in the `outputs` directory:

- `analysis_summary.txt` – dataset overview and numerical summary.
- `pivot_table.csv` – exported pivot table.
- `split_*.csv` – files created through dataset splitting.
- `visualizations/` – saved charts and graphs.

## Learning Outcomes

Through this project, I practiced:

- Working with Python libraries and external packages.
- Reading and processing CSV datasets.
- Handling missing values and duplicate records.
- Performing NumPy array operations.
- Applying statistical and mathematical functions.
- Manipulating and combining DataFrames.
- Creating charts using Matplotlib and Seaborn.
- Implementing exception handling and menu-driven programming.
- Exporting analysis results into files.

## Author

**Vaidika Ghoghari**

BCA Graduate | IT Professional

GitHub: [vaidika-ghoghari](https://github.com/vaidika-ghoghari)

## Connect With Me

- LinkedIn: [Visit My LinkedIn Profile](https://www.linkedin.com/in/vaidika-ghoghari-2196a534a)
- Email: [ghogharivaidika@gmail.com](mailto:ghogharivaidika@gmail.com)
- Project Explanation: [Add your project explanation video link]()

---

This project was developed for learning and practicing data analysis with Python.
