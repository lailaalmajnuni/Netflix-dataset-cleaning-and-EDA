
## Abstract
The goal of this project was to    

## Design
The project aimed to suggust top rated movies/TV shows listed on Netflix platform and get statistaical insights on the diversity of listed shows for new subscripers from different attruibutes point of view based on global Netflix dataset (date).

## Data
The dataset was obtained from https://www.kaggle.com/shivamb/netflix-shows?select=netflix_titles.csv and it had a size of (12 X 8807), however for the seek of this project the features were cut down to 7 features which are: Type, Title, Country, Date Added, Release Year, Rating and Listed in. I used an additional dataset to get the IMDb rating for the listed shows from IMDb website. Finalizing the prossess of joining the netflix and IMDb datasets, I ended up with a dataset of size (8 X 3177).

## Algorithms
- Joined multiple datasets.
- Checked for inconsistency in columns.
- Removed duplicates and some outliers.
- Dropped unnecessary columns and renamed others.
- Dropped null values and filled in some.

## Tools
- Used SQLite, Spyder, Jupyter Notebook, Python.
- Libraries: Numpy and Pandas for data manipulation and Matplotlib and Seaborn for plotting

## Communication
