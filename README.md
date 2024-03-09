# Data-Collection-challenge
## Part 1: Scrape Titles and Preview Text from Mars News
- Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data

## Part 2: Scrape and Analyse Mars Weather Data
- Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape.
- Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

- id: the identification number of a single transmission from the Curiosity rover
 - terrestrial_date: the date on Earth
 - sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
 - ls: the solar longitude
- month: the Martian month
- min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
- pressure: The atmospheric pressure at Curiosity's location
- Analyse your dataset by using Pandas functions to answer the following questions:
1. How many months exist on Mars?
```
{
  month
1     174
2     178
3     192
4     194
5     149
6     147
7     142
8     141
9     134
10    112
11    138
12    166
Name: count, dtype: int64
}
```
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- 1867
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 

![Average Temperature by Month](/Starter_Code/resources/average_temperature_by_month.png)

4. Which months have the lowest and the highest atmospheric pressure on Mars? 

![Average Temperature by Month](/Starter_Code/resources/average_temperature_by_month(coldest%20&%20hottest).png)

5. About how many terrestrial (Earth) days exist in a Martian year? 

![Average Temperature by Month](/Starter_Code/resources/Daily%20Minimum%20Temperature%20on%20Mars.png)


## References
 1. I have sought assistance from the support staff at Ask BCS on multiple occasions during the debugging process of the code. Their support has been invaluable in resolving various issues and ensuring the smooth progression of the tasks at hand. 
 2. [Mars news Website](https://static.bc-edx.com/data/web/mars_news/index.html)
 3. [Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html)