# Movie Ratings Analysis with Polars

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Polars](https://img.shields.io/badge/Polars-latest-CD792C)
![License](https://img.shields.io/badge/License-Apache%202.0-green)

## Overview
This project performs an end-to-end exploratory data analysis on the 
MovieLens dataset using Polars. The dataset contains movie ratings, 
tags, and metadata from real users, and the goal is to uncover 
meaningful patterns in user behavior, genre popularity, and 
rating distributions.

**Dataset:** 3 tables — movies, ratings, tags  
**Tools:** Python, Polars, Matplotlib

## Dataset
The dataset is sourced from the 
[MovieLens](https://grouplens.org/datasets/movielens/) 
dataset provided by GroupLens Research.

## Project Structure
movie-ratings-analysis-polars/
│

├── Movie_Ratings_Analysis_Polars.ipynb   # Main analysis notebook

└── README.md## Analysis Summary

### Data Preprocessing
- Verified missing values across all 3 tables — none found
- Verified duplicate records across all 3 tables — none found
- Dataset was clean and ready for analysis

### Exploratory Data Analysis
| Section | Key Finding |
|---|---|
| Rating distribution | Most users rate movies between 3.0 and 4.0 |
| Genre ratings | Film-Noir and War genres have the highest average ratings |
| User activity | Rating count per user varies significantly |
| Top rated movies | Classic and critically acclaimed films dominate |
| Tag analysis | Most common tags reflect themes and actor names |
| Genre popularity | Drama is the most common genre in the dataset |

## Tools & Libraries
- **Python 3.x**
- **Polars** — data manipulation and analysis
- **Matplotlib** — data visualization

## How to Run
1. Clone the repository
```bash
git clone https://github.com/UghurKhalilov/movie-ratings-analysis-polars.git
```
2. Open the notebook
```bash
jupyter notebook Movie_Ratings_Analysis_Polars.ipynb
```

## License
This project is licensed under the Apache License 2.0 — see the 
[LICENSE](LICENSE) file for details.

