
# IMDb Top 250 Movies Analysis

Scraping data from IMDb Top 250 Movies and getting some insights about them

## Description

This Poject had 3 phases : 

- Scraping data from [IMDB](https://www.imdb.com/chart/top/?ref_=nv_mv_250)
- Creating DataBase using MySQL and mysql.connector
- Analyzing gathered data and get some insights

### Data Scraping

I used both Selenium and bs4(BeautifulSoup) to scrape data such as :  
- title
- year
- parental guide
- runtime(in minutes)
- genre
- director
- writer
- star
- gross us canada

### DataBase Design

First I cleaned data and then used MySQL and mysql.connector to create following DataBase :
![IMDB_DB](https://github.com/MiladNooraei/IMDb-Top-250-Movies-Analysis/assets/108691050/64b676bc-7f25-4ac2-b1f4-7a48da5996ad)

### Analyzing

This Phase has 3 parts : 
1. Based on users input ->
- Filtering by movies release year
- Filtering by movies runtime
- Filtering by movies stars
- Filtering by movies genre

2. Static Plots ->
- 10 most selling Movie
- 5 most prolific actors
- Number of Genres
- Number of Parental Guide
- Number of each Genre for each Parental Guide

3. User Required Graph (Dynamic Plots) ->
- Top 10 Selling based on input Genre
- Word Cloud of Movies based on input Genre

