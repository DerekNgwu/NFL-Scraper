# NFL-Scraper

This script uses the requests library to send an HTTP GET request to the NFL website's URL, and the BeautifulSoup library to parse the HTML of the response. It then searches the parsed HTML for the table element containing the player stats data, and uses a loop to iterate through the rows of the table, extracting the data from the cells of each row. The csv library is used to create a CSV writer object, which is used to write the extracted data to a CSV file, with each row of the table being written as a row in the file and the data from each cell being written to the respective column. The first row of the file is a header row with column titles.


