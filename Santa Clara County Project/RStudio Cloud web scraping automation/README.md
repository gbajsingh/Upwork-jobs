# RStudio Cloud web scraping automation
Developed a tool to automatically output an excel file with web query results filled in a desired column. To accomplish the task I wrote a R script on RStudio cloud service.
The script takes the information(Addresses) from Property Address column; navigates to the desired website, performs a query on the website
and extracts the results back into same spreadsheet.

The script also saves the work in case the execution process is interupted because of code error/bug or simply loosing internet connection.
Which means it outputs an excel file with all the web searches performed before interuption.

The script also picks up from previous excel row where it was interrupted to avoid extracting already extracted data.