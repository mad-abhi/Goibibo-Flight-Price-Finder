# Flight Price Scraper

The **Flight Price Scraper** is a Python script designed to automate the process of finding the cheapest and shortest flight fares from the Goibibo website. The script utilizes web scraping techniques with the help of the Selenium and BeautifulSoup libraries to extract relevant information from the website.

## Features

1. **Cheapest Flight Fare:** The script extracts and displays the cheapest flight fare available for the specified parameters, including the departure and return dates, the number of adults, children, and infants.

2. **Shortest Duration Flight Fare:** Additionally, the script has the capability to switch to the option for sorting flights by the shortest duration and extract and display the corresponding fare.

## How It Works

1. **User Input:** The user provides details such as the starting and final destination, departure and return dates, and the number of adults, children, and infants.

2. **Web Scraping:** The script uses Selenium to automate the web browser (Chrome) and navigate to the Goibibo website with the provided parameters.

3. **Data Extraction:** BeautifulSoup is employed to parse the HTML content of the website and extract relevant information, such as flight fares.

4. **Output:** The script prints the extracted information, including the cheapest flight fare and the shortest duration flight fare, to the console.

## Usage

Users can run the script by following the instructions in the README. The script prompts users to input details such as the starting and final destination, travel dates, and passenger information. After execution, the script will display the cheapest and shortest duration flight fares.

## Contribution

Contributions to the project are welcome. Users can contribute by opening issues, suggesting improvements, or submitting pull requests to enhance the functionality or address any issues.


