# Data_Scraping_with_BeautifulSoup
---
This project is about web scraping using BeautifulSoup lib. To automate search and scrap, requests lib is used with headers that helps to mimic a real browser to bypass IP ban or scrap blocker.
The results in site has 3 pages, so it reads pages one by one, extracts data and stores in variable which will then concated in a single data. The data is then saved in .html file to perform scraping offline so that we dont have to request web incase of any data crash. The file is then read and soup object is created. Then we extract data like "Profile Group","Profile","State","Country" and store it in dict. The dict is then transformed to pandas DataFrame to extract into different forms.
