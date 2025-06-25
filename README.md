
# Munjya Review Analysis

This project scrapes and analyzes movie reviews from IMDb. It collects reviews and ratings from a specific movie page, performs sentiment analysis, and visualizes the distribution of ratings. The script uses Python and popular libraries such as `requests`, `BeautifulSoup`, `TextBlob`, and `matplotlib`.

## Features

- **Web Scraping**: Scrapes movie reviews and ratings from IMDb using `requests` and `BeautifulSoup`.
- **Sentiment Analysis**: Analyzes the sentiment of reviews (positive, negative, neutral) using `TextBlob`.
- **Data Visualization**: Visualizes the distribution of IMDb ratings using `matplotlib`.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/munjya-review-analysis.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Replace the `url` variable with the IMDb movie page you want to scrape:
   ```python
   url = 'https://www.imdb.com/title/tt27995594/reviews/?ref_=tt_ov_rt'
   ```

2. Run the script to scrape reviews, analyze sentiments, and plot the rating distribution:
   ```bash
   python munjya_review_analysis.py
   ```

## Output

- **Scraped Reviews**: Displays a list of reviews and their corresponding ratings.
- **Sentiment Analysis**: Prints the count of positive, negative, and neutral reviews.
- **Rating Distribution**: A histogram showing the distribution of ratings.

## Example

```bash
Scraped 100 reviews and ratings.
Positive reviews: 40
Negative reviews: 30
Neutral reviews: 30
Total reviews: 100
Positive reviews: 40.00%
Negative reviews: 30.00%
Neutral reviews: 30.00%
```

The histogram of ratings will be displayed as a plot.

## Dependencies

- `requests`
- `beautifulsoup4`
- `textblob`
- `matplotlib`

You can install all dependencies by running:
```bash
pip install requests beautifulsoup4 textblob matplotlib
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
