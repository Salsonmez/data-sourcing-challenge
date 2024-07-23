# data-sourcing-challenge
# Movie Review and Details Aggregator

This project aggregates movie reviews from the New York Times and detailed movie information from The Movie Database (TMDB) API. It merges these datasets and exports the combined data to a CSV file.


## Usage

1. Run the script to fetch movie reviews and details:

2. The script will:
    - Fetch movie reviews from the New York Times API.
    - Extract movie titles from the reviews.
    - Fetch detailed movie information from the TMDB API.
    - Merge the datasets.
    - Clean and format the data.
    - Export the combined data to a CSV file named `merged_data.csv`.

## Files

- `script_name.py`: The main script to run the data aggregation process.
- `.env`: File to store your API keys (not included, you need to create it).
- `final_list.csv`: The output CSV file with the merged data.


## Acknowledgements

- [New York Times API](https://developer.nytimes.com/apis)
- [The Movie Database (TMDB) API](https://developers.themoviedb.org/3)

