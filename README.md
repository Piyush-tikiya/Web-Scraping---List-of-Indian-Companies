# ***Web Scraping | List of Indian Companies***

## ***Problem Statement***
```
Manually collecting company information from websites is time-consuming and inefficient.

This project automates the process of extracting:

- Company Name
- Industry
- Sector
- Headquarters
- Founded Year
- Business Notes
- Company Link

from Wikipedia and stores it in a structured Excel format.

```

## ***Tech Stack Used***
```
- Python
- Requests
- BeautifulSoup (bs4)
- Pandas
- Excel (.xlsx)
```

## ***📂 Website Scraped***

*Source Website:*
   - *https://en.wikipedia.org/wiki/List_of_companies_of_India*

## ***🔍 Features***

- Browser-like Request Handling
- Used custom headers (User-Agent) to behave like a real browser and avoid request blocking.

## ***HTML Table Extraction***
```
- Located and extracted

- <table class="wikitable sortable">

along with:

- th → Table headings
- tr → Table rows
- td → Row values
- a href → Company profile links

- Dynamic Data Structuring
- Created dictionaries using: zip() to map column names with row values dynamically.
```
## ***Data Cleaning***
```
- Renamed columns for better readability.
- Final cleaned dataset exported using Dataframe.
```



## ***📸 Project Screenshot***

***https://github.com/Piyush-tikiya/Web-Scraping---List-of-Indian-Companies/blob/main/w.png?raw=true***

***https://github.com/Piyush-tikiya/Web-Scraping---List-of-Indian-Companies/blob/main/list_of_companies.png?raw=true***

## ***📁 Final Output***

```
- List_of_companies.xlsx
```
## ***💡 Key Learnings***
```
Through this project, I learned:

- Real-world web scraping techniques
- Parsing HTML tables efficiently
- Extracting hyperlinks dynamically
- Data cleaning using Pandas
- Exporting production-ready Excel files
- Writing cleaner and scalable scraping logic
```







## ***🤝 Connect With Me***
```

LinkedIn: www.linkedin.com/in/piyushtikiya07

GitHub: https://github.com/Piyush-tikiya
```
