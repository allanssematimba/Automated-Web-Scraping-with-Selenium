# Automated Web Scraping with Selenium

This Python project is an automated web scraping tool that extracts the price of a particular book listed on Amazon. It utilizes the Selenium library to automate the process of navigating to the book's page on Amazon, and then extracting the price of the paperback version of the book.

## How it Works
- The script opens a Chrome browser window and navigates to the NeuralNine website.
- It clicks on the "Books" menu item, and then clicks on the "7 in 1" book link.
- The script switches to the new tab that was opened and extracts the price of the paperback version of the book from Amazon's website.
- The price is then printed to the console.

## Tools Used
This project was built using Python and the following libraries:
- Selenium: A Python library for automating web browsers.
- ChromeDriver: A standalone server which implements WebDriver's wire protocol for Chromium.
- webdriver_manager: A library that helps you to download and install drivers like ChromeDriver.

## Requirements
- Python 3.6 or later
- Selenium 3.14.0 or later
- ChromeDriver 2.41 or later
- Google Chrome

## Contributing
If you find a bug or have a feature request, please submit an issue on the GitHub repository. Pull requests are welcome!
