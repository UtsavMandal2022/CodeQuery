# CodeQuery
This webpage finds you a desired cp question from leetcode using provided keywords. The backend is in flask and python. Uses TF-IDF algorithm.

Hosted link: https://codequery-cqzk.onrender.com/

This repository consists of only the app and projection part to the web, the scraping and TF-IDF repositories are separately made and below are the links given to them:

Link to the TF-IDF implementation to print on console: https://github.com/UtsavMandal2022/TF-IDF_implementation

Link to the Leetcode Scraper made to use for it : https://github.com/UtsavMandal2022/LeetCode_scraper

Link to the Codeforces Scraper made: https://github.com/UtsavMandal2022/CF_question_scraper

How to run the code locally:
(On terminal)
packages:
pip install flask flask-wtf

To run it simply run the app.py file or do python app.py and the local server will start on your device. Further open the link in the terminal to view the page.


Documentation:

Introduction:
The Competitive Programming Question Finder is a platform designed to efficiently search for competitive programming questions from platforms , currently LeetCode, using user-provided keywords. This documentation provides an overview of the platform's key features and the implementation details.

Key Features:
•	Efficiently finds competitive programming questions based on user-provided keywords.
•	Scrapes question data using Selenium package in Python.
•	Processes and filters the scraped data to remove unwanted noise.
•	Implements the TF-IDF algorithm to prioritize and weight terms based on their frequency and relevance.
•	Utilizes Flask framework for HTTP request/response handling and routing.
•	Implements wtforms library for form handling.
•	Uses HTML, CSS, and Flask templating for web page design.
•	Application deployment on OnRender.

Implementation Details:
The implementation of the Competitive Programming Question Finder involves several key components and steps:

Web Scraping:
•	The Selenium package in Python is used to scrape question data from platforms like LeetCode.
•	A scraper is developed to extract the href attribute and body text-content from anchor tags for each question.
•	The scraped data is processed to remove unwanted or noise data.
Data Structures:
•	Appropriate data structures are created in Python to handle the obtained question data.
•	These data structures enable efficient storage and retrieval of question information.
TF-IDF Algorithm:
•	The TF-IDF (Term Frequency-Inverse Document Frequency) algorithm is implemented to assign a priority order and weightage value to each term.
•	Term frequency represents the occurrence of a term within a document, while document frequency indicates the presence of a term across multiple documents.
•	The TF-IDF algorithm helps determine the relevance and importance of terms within the context of competitive programming questions.
Flask Framework:
•	The Flask framework is utilized for handling HTTP request/response and routing.
•	It provides a robust foundation for building web applications with Python.
•	The application's functionality is exposed through defined routes and endpoints.
wtforms and Web Design:
•	The wtforms library is used for form handling, allowing users to input keywords for question search.
•	HTML, CSS, and Flask templating are employed for designing the webpages.
•	The application's user interface is designed to provide an intuitive and user-friendly experience.

Deployment:
•	The application is deployed on the OnRender platform, making it accessible to users over the internet.

Conclusion:
The Competitive Programming Question Finder is a powerful platform that efficiently retrieves competitive programming questions based on user-provided keywords. With its web scraping, data processing, TF-IDF algorithm, and Flask-based web application implementation, it offers a seamless experience for programmers searching for relevant programming questions.
