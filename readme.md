# Zillow Scraper
"Recently sold" listings scraper from Zillow, using Selenium based on Chris Muir's [Zillow Scraper](https://github.com/ChrisMuir/Zillow).  The code takes as input search terms that would normally be entered on the Zillow recently_sold page.  It creates 12 variables for each home, saves them to a data frame, and then writes the df to a CSV file that gets saved to your working directory.

## Software requirements/info:
- This code was written using Python 3.5.x
- Scraping is done with Selenium v3.0.x, which can be downloaded here:
  http://www.seleniumhq.org/download/
- conda 4.3.29
downloaded here: https://conda.io/docs/user-guide/install/index.html
- The selenium package requires a webdriver program. This code was written
  using Chromedriver v2.25, which can be downloaded here:
  https://sites.google.com/a/chromium.org/chromedriver/downloads
Python packages
  pandas (conda install pandas)
  zipcode (conda install zipcode)

To run: python zillow_runfile.py from your working directory. Check for a CSV file once is complete

Keep an eye on the Captcha that zillow triggers every so often - If you get one, you have less than 30 seconds to complete the prompt and confirm that you are not a robot, or the listings will not be scraped
