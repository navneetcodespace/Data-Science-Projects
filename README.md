# Data Science Projects

This repository contains a collection of data science projects demonstrating various techniques in data analysis, exploration, and feature engineering using Python and Jupyter Notebooks.

## Table of Contents
- [Country Capstone Project](#country-capstone-project)
- [Feature Extraction](#feature-extraction)
- [Technologies](#technologies)
- [Getting Started](#getting-started)

---

## Country Capstone Project

### Overview
A comprehensive data analysis project exploring global country statistics and demographic information. This project analyzes 194 countries across 64 different features including geographical, economic, political, and health indicators.

### Dataset
- **File**: `Countries.csv`
- **Records**: 194 countries
- **Features**: 64 columns including:
  - **Geographic**: Latitude, Longitude, Region, Continent
  - **Administrative**: Country name (short & long form), Currency, Capital City, Demonym
  - **Land Use**: Agricultural land, Forest area, Land area, Rural/Urban land
  - **Economic**: GDP, Inflation, Unemployment, Tax revenue, Government debt
  - **Energy**: Electricity access, Renewable energy consumption, Fossil fuel usage, CO2 emissions
  - **Health**: Health expenditure, Life expectancy, Hospital beds, HIV incidence, Suicide rate
  - **Demographics**: Population, Birth rate, Death rate, Fertility rate, Median age, Gender distribution
  - **Political**: Democracy score, Democracy type, Press freedom index, Women in parliament
  - **Other**: Internet penetration, Armed forces, Military expenditure, Political leaders

### Key Questions Answered
- Identification of countries with highest and lowest populations
- Analysis of democratic scores across nations
- Correlation between economic indicators and quality of life metrics
- Geographic and political pattern recognition
- Demographic and health trends globally

### Technologies Used
- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Jupyter Notebook**: Interactive analysis environment

### Files
- `Countries.ipynb`: Complete analysis notebook
- `Countries.csv`: Raw dataset

---

## Feature Extraction

### Overview
A practical project focused on feature engineering techniques. This project demonstrates how to extract meaningful features from raw data using anime dataset, particularly extracting episode count information from complex text strings.

### Dataset
- **File**: `anime.csv`
- **Records**: Top 50 anime by ranking
- **Original Features**: 
  - Rank: Position in ranking (1-50)
  - Title: Full anime title with metadata embedded in text
  - Score: User rating score

### Project Goal
Extract structured features from unstructured text data:
- **Episodes**: Extract episode count from title strings (e.g., "64 eps" from complex title strings)
- Clean and normalize extracted data for analysis

### Feature Engineering Technique
The project implements a custom string parsing function to:
1. Locate episode information within parentheses in title strings
2. Extract the numeric portion and unit ("eps")
3. Clean the data by removing the "eps" suffix for numeric analysis
4. Create a new structured feature column

### Output
Resulting dataset with:
- Original Rank, Title, and Score columns
- New `Episodes` column with clean numeric/text data
- Data ready for further analysis and modeling

### Technologies Used
- **Python 3.x**
- **Pandas**: Data manipulation and feature creation
- **NumPy**: Numerical operations
- **String Processing**: Custom functions for text parsing and extraction
- **Jupyter Notebook**: Interactive development environment

### Files
- `FeatureExtraction.ipynb`: Complete feature engineering walkthrough
- `anime.csv`: Raw anime dataset

### Learning Outcomes
- Understanding of feature extraction from unstructured data
- Text parsing and string manipulation techniques
- Data cleaning and normalization best practices
- Practical regex and pattern matching concepts

---

## Technologies

This repository uses the following technologies and libraries:

| Technology | Version | Purpose |
|-----------|---------|---------|
| Python | 3.x | Programming language |
| Jupyter Notebook | Latest | Interactive development environment |
| Pandas | Latest | Data manipulation and analysis |
| NumPy | Latest | Numerical computing |

## Getting Started

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages (see below)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/navneetcodespace/Data-Science-Projects.git
cd Data-Science-Projects
```

2. Install required packages:
```bash
pip install pandas numpy jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open the desired notebook:
   - `Country Capstone Project/Countries.ipynb` - For country analysis
   - `Feature Extraction/FeatureExtraction.ipynb` - For feature engineering examples

### Usage

Each project is self-contained in its own directory with:
- A Jupyter Notebook file containing all analysis and code
- Associated CSV dataset file(s)

Simply open the notebook and run cells sequentially to reproduce the analysis.

---

## Project Insights

### Country Capstone Project Insights
- Demonstrates comprehensive exploratory data analysis (EDA)
- Shows data exploration across multiple dimensions
- Illustrates querying and filtering techniques
- Useful reference for analyzing multivariate datasets

### Feature Extraction Insights
- Practical example of handling real-world messy data
- Demonstrates importance of data preprocessing
- Shows custom feature engineering approaches
- Valuable for machine learning pipeline preparation

---

## Author
**navneetcodespace**

## License
This project is open source and available for educational and research purposes.

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork this repository and submit pull requests.

---

## Contact & Support
For questions or suggestions, please open an issue in the repository.

Happy Data Science Learning! 🚀
