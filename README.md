# Fandango Movie Ratings Analysis

    In this project, we analyze Fandango's movie ratings to investigate if there is any bias towards rating movies higher than they should be rated. The project uses data from 2015, and our goal is to see if we reach a similar conclusion to the one presented in the FiveThirtyEight article.

## Data

    The data comes from FiveThirtyEight's GitHub repository and consists of two CSV files:

    fandango_scrape.csv - Contains information about Fandango movie ratings.
    all_sites_scores.csv - Contains aggregate data for movie ratings from other sites, like Metacritic, IMDB, and Rotten Tomatoes.

## Dependencies

    To run the analysis, you will need the following libraries:

    NumPy
    Pandas
    Matplotlib
    Seaborn

## Analysis

    The project consists of three main parts:

    Exploring Fandango Displayed Scores vs. True User Ratings: In this part, we explore the Fandango movie ratings and investigate if there's any discrepancy between the displayed scores (stars) and the actual user ratings.

    Comparison of Fandango Ratings to Other Sites: In this part, we compare Fandango's movie ratings with the ratings from other popular movie rating websites, such as Rotten Tomatoes, Metacritic, and IMDB.

    Analyzing the Distribution of Scores Across Sites: Finally, we analyze the distribution of normalized movie ratings across all the websites and check if Fandango displays abnormally high ratings compared to other sites.

## Conclusion

    After analyzing the data, we find evidence supporting the claim that Fandango's ratings might be biased towards rating movies higher than they should be rated. The analysis shows that Fandango's displayed ratings (stars) tend to be higher than the true user ratings. Additionally, Fandango's ratings are generally higher than the ratings from other popular movie rating websites.
    Usage

    To run the Jupyter Notebook, make sure you have all the required dependencies installed and the data files (fandango_scrape.csv and all_sites_scores.csv) are in the same directory as the notebook. Then, open the notebook using Jupyter and run the cells sequentially to reproduce the analysis.

## Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


## Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
