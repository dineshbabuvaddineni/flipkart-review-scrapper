# Title: Flipkart Review Scraper

## Description
The Basic Flipkart Review Scraper is a simple web application built with Python, Flask, Beautiful Soup, HTML, and CSS. It provides an uncomplicated way for users to fetch and view product reviews from Flipkart with a user-friendly interface. 

## Features:

### Web Scraping with Beautiful Soup:
Utilizing Beautiful Soup, the application efficiently extracts review data from the Flipkart website. Beautiful Soup simplifies the process of parsing HTML and navigating the DOM, making it easier to collect relevant information.

### User-Friendly Web Interface:
The application is built using Flask, providing a simple and intuitive web interface. Users can input the Flipkart product URL or keywords to search for products, and the application will retrieve and display the corresponding reviews.

### Scraped Data Presentation:
Fetched reviews are presented in a clean and organized manner, making it easy for users to read and analyze. Information such as user ratings, comments, and timestamps are displayed for each review.


## Technologies Used:
1. Python: The core programming language for building the scraper and web application.
2. Flask: A lightweight web framework for creating the web interface.
3. Beautiful Soup: A Python library for web scraping purposes, used to parse HTML and extract data from Flipkart pages.
4. HTML: Used for creating the structure of the web pages.
5. CSS: Employed for styling the HTML elements and enhancing the overall visual appeal.

## Infrastructure Required.
1. VS Code (you can use any other IDE)
2. GIT
3. GITHUB

## How to run?

### Step 1: Clone the repository to your local machine.
```bash
git clone https://github.com/dineshbabuvaddineni/flipkart-review-scrapper.git
```

### Step 2 - Install the required dependencies using
```bash
pip install -r requirements.txt
```


### Step 3 - Run the Flask application using the command 
```bash
python app.py
```
### Step 4 -Access the web interface in your browser.
```bash
Open this link in browser: http://127.0.0.1:5000
```

### Note: you can view this URL in the recently generated log file and click on the link(ctrl+click) 

```
 A review csv file is automatically saved for each type of Product search.
```

## How to use:
1. Enter the Flipkart product keywords in the provided input field.
2. Click the "Search " button next to the input field.
3. The application will process the input and display the scraped reviews on the same page.
4. Users can easily read and analyze the reviews presented in a user-friendly format.

# Result:
## Home Page
<div>
<img src="https://github.com/dineshbabuvaddineni/flipkart-review-scrapper/blob/main/Project%20Images/HomePage.png" width="700" height="400" alt="Web Scraping"/>
</div>

## Review Page
<div>
<img src="https://github.com/dineshbabuvaddineni/flipkart-review-scrapper/blob/main/Project%20Images/Review%20Page.png" width="700" height="400" alt="Web Scraping"/>
</div>





