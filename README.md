# Web-scraping-BeautifulSoup
This Python script scrapes and extracts the titles and descriptions of technical blogs from the Draft.dev Learn Technical Blogs webpage. The data is saved in a CSV file for easy reference and analysis.

Features:

    Web Scraping: Utilizes requests and BeautifulSoup to fetch and parse webpage content.
    Data Extraction: Extracts blog titles (h3.post-title) and their descriptions (p.post-summary).
    Data Storage: Compiles the extracted data into a pandas DataFrame and exports it as a CSV file.

Key Libraries:

    requests: Fetches the webpage content.
    BeautifulSoup: Parses and extracts HTML content.
    pandas: Structures and saves the scraped data.

Output: 

    The script generates a CSV file named Best_Technical_Blogs.csv containing the following columns.

    Best Technical Blogs: Titles of the blogs.
    Description: Summaries of the blogs.

How to Use:

    Clone this repository and ensure Python is installed.
    Install the required libraries if not already installed - pip install requests beautifulsoup4 pandas
