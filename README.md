
# Movie Data Web Scrapper

The following project was a study case to pratice web scraping using python and verify wich library was the best for creating and editing a Excel Sheet in this particular case, inputing the website data into the Excel Sheet and creating a Filter and a Bar Chart, so, to do this, the following libraries were used:

* os
* requests
* bs4 - Beautiful Soup 4
* openpyxl
* xlsxwriter

Also, to compare both of them, two versions of the python script were made, one using xlsxwriter library and the other one using openpyxl.
## How the Code Works

In both scripts, this was the steps made to achieve the final result:

* Open Navigator
* Get into the website (https://www.boxofficemojo.com/chart/top_lifetime_gross/?area=XWW)
* Scrap the table data
* Create folder that will receive the Excel File
* Create Excel File
* Input Data into the Excel Sheet
* Process Data
* Input Process Data into a Second Excel Sheet
* Create Filter
* Create and Plot Bar Chart
## Authors

- [@simionattovini](https://github.com/simionattovini)
- [@TBFELIPE](https://github.com/TBFELIPE)
- [Salum28](https://github.com/Salum28)


