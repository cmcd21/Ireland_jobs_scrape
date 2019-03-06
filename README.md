# ireland_jobs

This project scrapes current Data Science job listings off [IrishJobs.ie](https://www.irishjobs.ie/) and [NIjobs.com](https://www.nijobs.com/). The data is stored as a data frame and is cleaned for further analysis.

-	Data scraped, parsed and stored in a data frame
-	Duplicate rows and NaN’s identified and dealt with
-	New columns created, and some columns joined, depending on data in related columns
-	Whitespace and unnecessary scraped characters dropped

This program does not only wokr for Data Scientist job listings. Any job can be assigned to *job_title* in cell 2

## Python libraries used
- requests
- bs4
- pandas
- numpy
- time
