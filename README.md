# gdp-scraper-wikipedia

## Project Overview
This project gets the GDP data of countries from a saved Wikipedia page by using Pandas to read the tables on the page. The data is cleaned and processed to find the top 10 countries by GDP, convert the numbers to billions, and save the results in a CSV file.

---

## Data Source
The data comes from this archived Wikipedia page:  
https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29

---

## Tools Used
- Python 3  
- Pandas (to read and process tables)  
- NumPy (for number calculations)
- lxml (for parsing) 

---

## What the Project Does
- Reads all tables from the Wikipedia page using Pandas.  
- Finds the correct table with GDP data.  
- Keeps only the country names and GDP numbers.  
- Changes GDP numbers from millions to billions and rounds them.  
- Picks the top 10 countries by GDP and saves the data.

---

## Sample Output

| Country        | GDP (Billion USD) |
|----------------|-------------------|
| United States  | 26854.60          |
| China          | 19373.59          |
| Japan          | 4409.74           |
| Germany        | 4308.85           |
| India          | 3736.88           |
| United Kingdom | 3158.94           |
| France         | 2923.49           |
| Italy          | 2169.74           |
| Canada         | 2089.67           |
| Brazil         | 2081.24           |


