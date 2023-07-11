
# TikTok-Top100-Hashtag-Scraper
This repository contains a Python script for scraping and analyzing the top 100 hashtags on TikTok from a saved HTML page. The script uses BeautifulSoup4 for parsing the HTML data, extracts relevant information about each hashtag, and stores the data in a Pandas DataFrame for further analysis.

Key features of the script include:

1. Extracting key metrics such as hashtag, category, trend status, post count, view count, and top creators.
2. Converting scraped data into a Pandas DataFrame.
3. Ability to filter and sort hashtags based on their metrics. For example, it can sort hashtags based on the least number of posts.

Please note that the script assumes that the HTML page structure of the source matches the expected structure. If TikTok updates their site, the script may need to be updated accordingly.

## Usage
First, save the HTML page that contains the top 100 TikTok hashtags on your computer. Then, modify the `file_path` variable in the script to match the location where you saved the HTML page.

Run the script with a Python interpreter. The script will read the HTML file, extract the data, and print the DataFrame with the hashtags information. To filter or sort the DataFrame, modify the `filter_hashtags` function according to your needs.

## Requirements
- Python 3.6+
- pandas
- BeautifulSoup4

This project is intended for educational and research purposes.

## Contributions
Contributions, issues, and feature requests are welcome!

Feel free to check [issues page](../../issues) if you want to contribute.

## License
[MIT](../../LICENSE)

## Contact
Karam - hello@karam.digital

Project Link: [https://github.com/KaramW/TikTok-Hashtag-Scraper](https://github.com/KaramW/TikTok-Hashtag-Scraper)

