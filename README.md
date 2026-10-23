# Netflix Content Explorer

A menu-driven Python data-analysis project that explores the Netflix Titles dataset using Pandas and NumPy.

## Features

- Counts Movies and TV Shows
- Shows titles added each year
- Finds the top 10 producing countries
- Identifies the top 5 most common genres
- Displays rating distribution
- Finds the oldest and newest release years
- Searches titles by keyword
- Filters content added in a selected year
- Counts total unique countries
- Calculates release-year statistics using NumPy

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook / Google Colab

## Dataset

Netflix Titles Dataset from Kaggle:

https://www.kaggle.com/datasets/shivamb/netflix-shows

## How to Run

1. Download or clone this repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download `netflix_titles.csv` from the Kaggle dataset link above.
4. Open `netflix_analysis.ipynb` using Jupyter Notebook or Google Colab.
5. Upload the CSV file when prompted or update the file path in the notebook.
6. Run all cells from top to bottom.
7. Use the interactive menu and choose options 1–10; enter `0` to quit.

## Data Cleaning

- Missing `country` values are replaced with `Unknown`
- Missing `director` and `cast` values are replaced with `Not Listed`
- Missing `rating` values are replaced with `Not Rated`
- Rows without `date_added` are removed
- A `year_added` column is extracted from `date_added`

## Author

**Saad Sk**  
B.Tech CSE — Artificial Intelligence and Machine Learning
