# Maritime Vessel Route Simulation & Data Engineering Challenge

## Author
**Tejas P B**  
Email: tejaspb12@gmail.com

## Project Overview
This project is a comprehensive data engineering and exploratory data analysis (EDA) challenge focused on maritime vessel routes and port data. Using a real-world port dataset, the notebook demonstrates data cleaning, transformation, and insightful statistical exploration, providing a foundation for further maritime analytics or machine learning applications.

## Features
- **Data Cleaning:**
  - Removes columns with more than 60% zero, blank, or 'Unknown' values.
- **Exploratory Data Analysis (EDA):**
  - Displays dataset structure, summary statistics, and key distributions.
  - Visualizes and summarizes both numerical and categorical port attributes.
- **Reusable Functions:**
  - Modular code for cleaning and analyzing datasets.

## Dataset
- **Source:** `UpdatedPub150.csv`
- **Description:** Contains global port information, including port names, locations, facilities, and navigational data.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- searoute
- pyais

Install dependencies using pip:
```bash
pip install pandas numpy seaborn matplotlib searoute pyais
```

## Usage
1. Clone or download this repository.
2. Place the `UpdatedPub150.csv` dataset in the project directory as referenced in the notebook.
3. Open `TEJAS_Blurgs.ipynb` in Jupyter Notebook.
4. Run the notebook cells sequentially to:
    - Install required packages (if not already installed)
    - Load and clean the dataset
    - Perform exploratory data analysis

## Project Structure
- `TEJAS_Blurgs.ipynb` : Main Jupyter Notebook with all code and analysis.
- `UpdatedPub150.csv` : Port dataset (not included, user must provide).
- `README.md` : Project documentation (this file).

## Notable Code Sections
- **Data Cleaning Function:**
  - Drops columns with excessive missing or irrelevant values.
- **EDA:**
  - Summarizes numerical and categorical features.
  - Visualizes dataset structure and key statistics.

## Example Outputs
- Head of the cleaned dataset
- DataFrame info (shape, columns, types)
- Descriptive statistics for numerical/categorical columns
- Visualizations (if included in the notebook)

## Contact
For questions or collaborations, contact Tejas P B at [tejaspb12@gmail.com](mailto:tejaspb12@gmail.com).

---
