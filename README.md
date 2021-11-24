# Assignment_Mindgo_Tech_Private_Limited
Assignment by chintamaneni shanmukh chowdary

Mindgo Tech Private Limited 
Internshala Assignment
Create a basic web crawler to crawl any particular website and store information in any file format (CSV will be better) .

Chintamaneni Shanmukh Chowdary, K L University
Phone: 9182476746

Working Procedure of my basic web crawler
•	First, all required python packages like BeautifulSoup for web crawling, requests for sending and getting HTTP response from the web page, pandas for structuring the data in the form of table using data frame, csv package for creating, writing, reading csv files are imported.
•	Then, a HTTP request was sent to URL (https://www.iplt20.com/stats/all-time/most-sixes) and received the response by using GET method. Then the response is parsed using HTML parser to get HTML content. This content is called as soup.
•	Then, by using the find function by passing “table” as argument, Received the table contents. Then found the table headings in it by  using the find function by passing “th” as argument. Then found the table data in it by  using the find function by passing “td” as argument.
•	Then, this data is stored in the form of table by using the data frame in pandas.
•	Finally, this data is written into the csv file named (Most_Sixes_In_IPL.csv).

