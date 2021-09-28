## Using Selenium and Python to scrape products metadata on Tiki website

The idea of scraping data with Python often comes along with Beautiful Soup. However, when dealing with dynamic scraping, which uses an actual browser and allows reading content that has been generated or modified via JavaScript, Selenium WebDriver is a good choice. Selenium a library which will interface with the browser, allow for the site to render, and then allow you to retrieve the data from the browser's DOM.

## Task
- Take in an URL and return a pandas dataframe
- The final dataframe should contain the following informations:
  - Product Name
  - Price
  - URL of the product image
  - URL of that product page
  - TIKI FAST badge (True/False)
  - Best-deal badge (True/False)
  - Payment on installment (True/False)
  - Discount Percentage
  
