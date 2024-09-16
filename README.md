Indeed Job Listings Scraper
Project Description
This project is a web scraper that extracts job listings from the Indeed website. It uses Selenium and BeautifulSoup to navigate job listings, extract details such as job titles, company names, locations, and salaries, and then processes this information for further analysis or display.

Features:

- Scraping Job Listings: Extracts job titles, company names, locations, and salaries.
- Supports Multiple Pages: Handles pagination to scrape job listings from multiple pages.
- Customizable User-Agent: Uses a customizable User-Agent string to mimic real browser requests.
 
Requirements:

- Python 3.8 or higher
- Selenium
- BeautifulSoup4
- Microsoft Edge WebDriver

Installation:

- Clone the Repository : git clone <repository-url>
- Navigate to the Project Directory : cd <project-directory>
- Create and Activate a Virtual Environment : python -m venv venv
- Install Required Packages : pip install -r requirements.txt
- Download Microsoft Edge WebDriver


Configuration:

- Update WebDriver Path : edge_service = Service(r'C:/path/to/edgedriver_win32/msedgedriver.exe')
  
