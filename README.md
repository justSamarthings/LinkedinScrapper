# LinkedIn Job Details Scraper

## Overview
This simple Python script uses Selenium to scrape job details from LinkedIn based on specific search criteria. The script is designed to extract information such as company names and job titles and save the results to a CSV file.

## Prerequisites
- Python
- Selenium
- ChromeDriver (Ensure you have the correct version compatible with your Chrome browser)

## Installation
1. Install Python: [Download Python](https://www.python.org/downloads/)
2. Install Selenium: `pip install selenium`
3. Download ChromeDriver: [ChromeDriver Downloads](https://sites.google.com/chromium.org/driver/)

## Usage
1. Replace the `executable_path` in the script with the path to your ChromeDriver executable.
   ```python
   driver = webdriver.Chrome(executable_path=r'path/to/chromedriver.exe')
   ```

2. Modify the `url` variable with the LinkedIn job search URL of your choice.
   ```python
   url = 'your_linkedin_job_search_url'
   ```

3. Run the script.

## Code Explanation
- The script uses Selenium to automate the web browser and navigate to the LinkedIn job search page.
- It scrolls through the page to load more job results dynamically.
- It extracts the company names and job titles from the search results.
- The extracted data is then saved to a CSV file named 'Linkedinjob.csv'.

## Example
You can use the provided URLs (`url1` and `url2`) in the code as examples. Ensure that you have the correct ChromeDriver version for your Chrome browser.

**Note**: Web scraping may violate the terms of service of the website. Ensure that you have the right to scrape the data, and use the script responsibly.

Feel free to customize the script according to your needs or add error handling for a more robust solution.
