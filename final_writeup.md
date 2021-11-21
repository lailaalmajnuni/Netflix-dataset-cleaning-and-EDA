
## Abstract
The goal of this project was to statistically analyze Netflix dataset and take a closer look at the content listed on the platform from different attributes point of view. The EDA revealed useful information on the distribution and diversity of netflix content for new subscribers to take a quick look at. Finally, recommended the top three shows based on genres at the end.

## Design
The project aimed to suggust top rated movies/TV shows listed on Netflix platform and get statistaical insights on the diversity of listed shows for new subscribers from different attruibute point of view based on global Netflix dataset collected from 1925 to 2021.

## Data
The dataset was obtained from https://www.kaggle.com/shivamb/netflix-shows?select=netflix_titles.csv and it had a size of (12 X 8807), however for the seek of this project the features were cut down to 7 features which are: Type, Title, Country, Date Added, Release Year, Rating and Listed in. I used an additional dataset to get the IMDb rating for the listed contens from IMDb website. Finalizing the prossess of joining the netflix and IMDb datasets, I ended up with a dataset of size (8 X 3177).

## Algorithms
- Joined multiple datasets.
- Checked for inconsistency in columns.
- Removed duplicates and some outliers.
- Dropped unnecessary columns and renamed others.
- Filled some null values and dropped others.

## Tools
- Used SQLite, Spyder, Jupyter Notebook, Python.
- Libraries: Numpy and Pandas for data manipulation and Matplotlib and Seaborn for plotting

## Communication
- The average weighted IMDb rate (score 0-10) was distrubuted normally, which means most of the listed shows are 6-7.
- The number of releasing movies/TV shows increaseed exponentailly on the period of 1960 to 2020.
- The diversity of content in countires is a bonus for subscribes who like exploring different cultrues through media. Keeping in mind United States and India are the most common.
- 90% of the listed contents are movies.
- January, November, and December are the months when netflix add more content. (best months to subscribe)
- Most common genres on Netflix are Dramas, International movies, Comedies.
- List of Recommendation Based on statistical analysis:

![image](https://user-images.githubusercontent.com/32347958/142750009-69fa57c1-1446-4c89-be1c-4592416b131b.png)

![image](https://user-images.githubusercontent.com/32347958/142750047-1e398ff1-178e-498d-968d-61b8ad76074d.png)
