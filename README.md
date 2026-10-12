# Kerala Rainfall & Climate Pattern Analysis Using Python

## PROJECT OVERVIEW

The **Kerala Rainfall & Climate Pattern Analysis Using Python** project explores rainfall patterns in Kerala using Exploratory Data Analysis (EDA). The project analyzes rainfall observations from 2021 to 2025 to understand rainfall distribution, seasonal variations, district-wise differences, monthly patterns, and heavy rainfall events.

Using Python data analysis and visualization libraries, this project transforms rainfall data into meaningful insights that help identify trends and variations in recorded rainfall.

## OBJECTIVES

- Analyze the distribution of daily rainfall observations.
- Identify yearly and monthly rainfall patterns.
- Study rainfall variations across different seasons.
- Compare average recorded rainfall across districts.
- Analyze Southwest and Northeast Monsoon rainfall patterns.
- Identify months, years, and districts with frequent heavy rainfall events.
- Examine extreme rainfall observations.
- Develop data analysis and visualization skills using Python.

## DATASET INFORMATION

- **Dataset:** Kerala Daily Rainfall Data
- **Study Period:** 2021–2025
- **Data Format:** CSV
- **Main Rainfall Column:** `Manual Daily Rainfall (mm)`
- **Date Column:** `Data Acquisition Time`
- **Geographical Information:** District, Station, Tehsil, Block, Latitude, Longitude
- **Other Information:** River, Basin, Tributary, and related fields

**Important:** The 2025 records are incomplete, with several months having no recorded observations. Therefore, yearly and monthly comparisons involving 2025 should be interpreted cautiously. Missing observations are not treated as zero rainfall.

## TECHNOLOGIES USED

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and aggregation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis environment

## PROJECT WORKFLOW

1. Import the required Python libraries.
2. Load the rainfall dataset.
3. Understand the dataset structure and data types.
4. Check for missing values and duplicate records.
5. Convert date columns into datetime format.
6. Extract year, month, month name, and day.
7. Create seasonal categories.
8. Perform univariate and comparative analysis.
9. Visualize rainfall trends and distributions.
10. Analyze heavy rainfall events and extreme observations.
11. Summarize the major findings.

## EXPLORATORY DATA ANALYSIS

The project investigates the following areas:

### 1. Rainfall Distribution
- Distribution of daily rainfall observations
- Identification of extreme rainfall values
- Basic statistical analysis of rainfall

### 2. Yearly and Monthly Analysis
- Number of rainfall records available each year
- Average recorded rainfall by year
- Monthly rainfall patterns
- Comparison of monthly rainfall across years

### 3. Seasonal Analysis
- Average rainfall across seasons
- Seasonal rainfall changes across years
- Southwest Monsoon analysis
- Northeast Monsoon analysis
- Comparison of the two monsoon seasons

### 4. District-Wise Analysis
- Average recorded rainfall by district
- District-wise rainfall differences
- Rainfall variability across districts
- Comparison of district rainfall patterns across years

### 5. Heavy Rainfall Analysis
For this analysis, a heavy rainfall event is defined as an observation with rainfall **greater than or equal to 50 mm**.

The analysis examines:
- Monthly frequency of heavy rainfall events
- Yearly frequency of heavy rainfall events
- District-wise frequency of heavy rainfall events
- Maximum recorded rainfall observation

## DATA VISUALIZATION

The project uses different charts to explore rainfall patterns:

- Histograms
- Box plots
- Bar charts
- Grouped bar charts
- Line charts
- Heatmaps

These visualizations help compare rainfall observations and identify patterns, differences, and extreme values.

## KEY INSIGHTS

The analysis is designed to identify:

- Variations in average recorded rainfall across years
- Months with higher average recorded rainfall
- Seasonal differences in rainfall
- Districts with different average rainfall levels
- Changes in rainfall patterns across the available observation period
- Months, years, and districts with more frequent heavy rainfall observations
- Extreme rainfall values in the dataset

The actual findings should be interpreted from the generated charts and calculated results. In particular, incomplete 2025 records may affect comparisons with earlier years.

## HOW TO RUN THE PROJECT

### Prerequisites

Install Python and Jupyter Notebook, or use Anaconda to manage your Python environment.

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your repository URL.

### Step 2: Navigate to the Project Folder

```bash
cd YOUR_PROJECT_FOLDER
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Add the Dataset

Place the rainfall CSV file in the same folder as the Jupyter Notebook, or update the dataset path in the notebook.

### Step 5: Open Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook:

`Kerala_Rainfall_Climate_Pattern_Analysis.ipynb`

Run the cells in order to reproduce the analysis and visualizations.

## PROJECT STRUCTURE

```text
Kerala-Rainfall-Climate-Analysis/
│
├── Kerala_Rainfall_Climate_Pattern_Analysis.ipynb
├── rainfall_manual_daily_kerala_sw_kl_2021_2025.csv
└── README.md
```

*The CSV filename above should match the actual dataset filename you upload. If the dataset is not included in the repository, provide instructions for obtaining it.*

## CONCLUSION

This project demonstrates how Python can be used to explore rainfall data, compare recorded rainfall patterns, analyze seasonal and district-wise variations, and identify heavy rainfall observations.

Through Exploratory Data Analysis and data visualization, the project provides a structured approach to understanding the available Kerala rainfall dataset. It also highlights the importance of data completeness when interpreting trends and making comparisons across years.

## SKILLS DEMONSTRATED

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- Data Aggregation
- Statistical Analysis
- Data Visualization
- Time-Based Analysis
- Python Programming
- Insight Generation

