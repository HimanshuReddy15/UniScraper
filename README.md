This project is a web scraper that extracts information about universities from the Yocket website. It uses the requests library to fetch the HTML content of a university's page and the BeautifulSoup library to parse the HTML and extract relevant information such as the university's name, location, address, email, courses offered, and ranking.

The extracted data is then stored in a CSV file named Uni_Details.csv.

Here's a breakdown of the steps involved:

Import Libraries: Import necessary libraries like requests, BeautifulSoup, datetime, time, and smtplib.
Fetch Website Data: Connect to the Yocket website using the requests library, retrieve the page content, and parse it using BeautifulSoup.
Extract Information: Extract specific data like university name, place, location, details, courses, address, and email using BeautifulSoup's functions to locate HTML elements by their class or tag.
Store the Data: Write the extracted data to a CSV file named Uni_Details.csv using the csv library.
Read the Data (Optional): The code also includes an optional step to read the CSV file using pandas to view the stored data as a dataframe.
This project can be useful for gathering data about universities for research, analysis, or comparison. By changing the URL in the code, you can target different universities on the Yocket website and scrape their information.

This project is for educational purposes only. Web scraping should be done responsibly and with respect for the website's terms of service.
