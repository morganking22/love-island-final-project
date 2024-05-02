# love-island-final-project

## Description of Project
The content of this page consists of a project of web scraping the [Love Island Fandom](https://loveisland.fandom.com/wiki) webpage via each individual Love Island UK’s [contestant page](https://github.com/morganking22/love-island-final-project/blob/main/contestant_url.txt). After web scraping the information, I transformed the birthdate data to determine each contestant’s Zodiac sign. I then compiled all of the data into one CSV which I utilized to create [data visualizations](https://github.com/morganking22/love-island-final-project/tree/main/Data%20Visualizations).

## Data:

- [contestant_url.txt](https://github.com/morganking22/love-island-final-project/blob/main/contestant_url.txt) contains all of the URLs that were web scraped for the project.
- [all_data.csv](https://github.com/morganking22/love-island-final-project/blob/main/all_data.csv) contains all of the data compiled for this project.

## Code:

- [love_island_contestant_function.ipynb](https://github.com/morganking22/love-island-final-project/blob/main/love_island_contestant_function.ipynb) is the initial code utilized to web scrape.
- [convert_birthdate.ipynb](https://github.com/morganking22/love-island-final-project/blob/main/convert_birthdate.ipynb) was used to convert long form dates to DD-MM-YYYY.
- [zodiac-signs.ipynb](https://github.com/morganking22/love-island-final-project/blob/main/zodiac-signs.ipynb) was used to convert the date into the zodiac sign of each contestant.
    - This code was modelled from GitHub user [Crusat](https://github.com/crusat)'s [Python Zodiac Code](https://github.com/crusat/python-zodiac-sign/tree/master)
- [love_island_csv_cleanup.ipynb](https://github.com/morganking22/love-island-final-project/blob/main/love_island_csv_cleanup.ipynb) was used to clean up the data and create data visualizations.
