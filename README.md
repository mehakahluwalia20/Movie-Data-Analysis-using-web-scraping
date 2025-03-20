# Movie Data Analysis Using Web Scraping  

# Project Overview  
This project scrapes IMDb’s Top 1000 movies using BeautifulSoup and requests, extracting key details such as:  

- Movie Title  
- Year of Release  
- Runtime  
- IMDb Rating  
- Metascore  
- Votes and Gross Earnings  
- Short Description  

The extracted data is stored in a Pandas DataFrame for further analysis, visualization, or insights into movie trends.  

# Features  

- Web Scraping with BeautifulSoup to extract structured movie data from IMDb  
- Dynamic URL Handling to iterate over multiple IMDb pages for large-scale data collection  
- Automated Data Cleaning and Processing to format extracted data for easy analysis  
- Data Storage in Pandas DataFrame for further manipulation, visualization, and export to CSV or Excel  
- Randomized Request Delays to prevent being blocked by IMDb servers  

# Tech Stack  

- Python  
- BeautifulSoup and Requests for Web Scraping  
- Pandas and NumPy for Data Processing  

# How It Works  

1. The script requests IMDb’s Top 1000 movies webpage and parses the HTML using BeautifulSoup.  
2. Extracts movie details including title, year, rating, runtime, votes, and more.  
3. Stores data in a structured Pandas DataFrame for analysis.  
4. Saves results to an Excel or CSV file for further use.  

# Example Output (Pandas DataFrame)  

| Movie Name | Year | Runtime | Rating | Metascore | Votes | Gross | Description |  
|------------|------|---------|--------|-----------|--------|--------|-------------|  
| The Shawshank Redemption | 1994 | 142 min | 9.3 | 80 | 2.5M | $28.3M | Two imprisoned men bond... |  

# Future Enhancements  

- Data Visualization to graph movie trends, ratings, and earnings  
- Genre-Based Analysis to scrape genre information for deeper insights  
- Sentiment Analysis using NLP on descriptions for better understanding of reviews  
