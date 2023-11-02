# WEB SCRAPING : LinkedIn

### Project Description : This is a project where I leveraged my advanced Python skills to web-scrape LinkedIn's website using Selenium.

This project is dedicated to scrapping one of the most used networking platforms in the business world, LinkedIn.

This project is a web scraping script built with Python to **extract job listings of Data scientist roles in Barcelona** from LinkedIn. It uses the **```selenium```** package to automate browser actions and extract data from dynamic web pages.

I extract the following through scraping :
- **job title**
- **company name**
- **location**  
- **workspace** 
- **promoted status**
- **application source**
- **job posting state**
- **posting date**
- **number of applicants**
- **whether the job requires Python**
- **employment type, seniority level**
- **number of employees**
- **industry**.

The extracted data is stored in lists and then converted to a **Pandas dataframe** for easy analysis.

## Requirements :
- LinkedIn account
- selenium
- beautifulsoup4
- pandas
- tqdm
- Additionally, the chromedriver executable file needs to be installed on the system and its path should be added to the PATH environment variable. 
