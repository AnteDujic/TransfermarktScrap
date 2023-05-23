# Web Scraping Transfermarkt

This project demonstrates web scraping using Python to extract data from Transfermarkt, a popular website specializing in football player and team statistics, transfers, and market values. The extracted data will be used to create a dataset of players in the Croatian football league (Supersport HNL) for further analysis.

## Steps to Create the Web Scraper

### Step 1: Identifying the Target Data
The objective is to extract data on all players in the Croatian football league. The desired information includes player names, age, nationality, position, height, and more. The data will be collected by navigating to each club's URL.

### Step 2: Inspect the Structure of the Website
Before writing the code, it's important to inspect the website's structure using browser developer tools. This allows us to observe the actual webpage and validate our understanding of its structure. The parsed HTML structure will be used to extract the relevant data, accessing specific elements, retrieving their attributes or text content, and navigating through the HTML structure.

### Step 3: Write Code to Navigate Through the HTML Structure
In this step, we will write the code for the web scraper. The process is divided into two stages: constructing the club URLs and scraping player data. We will import the necessary libraries, construct the URLs for data collection, and then scrape the data from those URLs to create a comprehensive database.

### Step 4: Creating a DataFrame
Once the data is scraped, it can be organized and structured using a DataFrame. Python's pandas library is commonly used for this purpose. The scraped data will be transformed into a structured format, allowing for easier analysis and manipulation.

### Step 5: Exporting the Data to CSV
Finally, the extracted data will be exported to a CSV file for further analysis. CSV (Comma-Separated Values) is a widely supported file format that can be easily imported into various data analysis tools or programming languages.

## How to Use This Repository

1. Clone the repository to your local machine.

2. Install the required dependencies by running `pip install -r requirements.txt`.

3. Open the Jupyter Notebook file `SuperSport_HNL.ipynb`.

4. Alternatively, you can also access the notebook on nbviewer by clicking the following link: [View on nbviewer](https://nbviewer.org/github/AnteDujic/TransfermarktScrap/blob/main/SuperSport_HNL.ipynb).

## Disclaimer
This project is designed for educational purposes only. The extracted data should not be used for any other means beyond learning and exploration. Respect the website's terms of service and scrape responsibly.
