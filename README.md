Video link https://www.loom.com/share/afd03f696ad94c4184d2e9e11ba1c22a
The robot is used to automate the process of  https://www.semanticscholar.org/ literature collection for the user-defined topic. Result of the process is an email with attached excel with info about each found article.

### Used libraries
- selenium - web-browser automation
- pandas - work with datatables
- smtplib \ email - email creating and sending
- BeautifulSoup

### Algorithm
- User defines a topic, number of pages, and receiver of the resulting email
- Robot creates links for each search results page
- Robot collects links to the articles from each page
- Robot scraps article's info and downloads source docs if available
- Robot writes all info to excel and sends email

### How to use
- Clone git repository to your computer
- Create a virtual environment (optional)
- Install packages from requirements.txt
- Make setup correcting conf.py file
- Run script rpa.py
