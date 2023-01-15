# Web Scraping IMDb Top Rated Movies

## Scraped IMDb official site to get Top ranking movies on trend using requests, BeautifulSoup

**Scraping IMDb Top 250 Movies**
**What is web scraping?**

Web scraping is an automated method used to extract large amounts of data from websites. The data on the websites are unstructured. Web scraping helps collect these unstructured data and store it in a structured form.

**What is IMDb?**

The Internet Movie Database (IMDb) is an online database containing information and statistics about movies, TV shows and video games as well as actors, directors and other film industry professionals. This information can include lists of cast and crew members, movie release dates and box office information, plot summaries, trailers, actor and director biographies and other trivia.

Information on IMDb comes from a variety of sources, such as filmmakers, film studios, on-screen credits and other official sources. However, much of the information comes from IMDb users themselves, who can submit facts in a wiki-style format. Unlike traditional wiki sites, IMDb always authenticates information before it appears online -- although errors do show up, and the website allows users to report possible mistakes so they can be fixed.



### Libraries Used

**Here, we will use Python libraries:-**

- requests To download a web page,
- beasutifulSoup4 in order to extract data from the webpage and
- pandas, It provides various data structures and operations for manipulating numerical data and time series.

## Project Outline:
- We are going to scrape https://www.imdb.com/chart/top/ and Download the webpage using 'requests'.
- Parse the HTML source code using 'beautifulSoup4'.
- We will get movie name and URL
- Compile the extracted information into Python list and dictionaries.
- Convert the Python dictionaries into Pandas DataFrames.
- Finally we'll create a CSV file in the following format:
- Movie Name, Url, Released On, Rating
The Shawshank Redemption, https://www.imdb.com/title/tt0111161/, 1994 , 9.2

_**We can execute this code using the "Run" button at the top of the page**_

1. Use the requests library to download web pages
Use requests to download the page
Use bs4 to parse and extract information
Convert to a pandas dataframe
check out -- https://jovian.ai/sritu1510/scraping-imdb-top-250-movies
