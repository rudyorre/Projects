## Tools
* [Tabula](https://tabula.technology/)
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)

## Data Source
All data has been scraped from the pdf files for retention rates of each semester from
[El Camino's Course Completion site](https://www.elcamino.edu/about/depts/ir/acadperformance.aspx).

## Data Collection
I used [Tabula](https://tabula.technology/) for its simplicity and ease of use, however some of the
rows were shifted to the right by 1 or 2 columns, so I had to manually adjust those rows. Currently
running into an issue where non-ASCII characters are screwing up loading into a Pandas dataframe.

## Data Exploration
