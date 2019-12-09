The main rar file contains all of my code for my scraper. 

For this project, I am scraping the following website:

https://ccom.ucsd.edu/~acloninger/170A_F19/Math170A_homework.html

The directory test2 --> test2 --> spiders contains the 'spider2' file.

Usage:

run 'scrapy crawl spider2' and let the spider run on the website. 

My crawler goes through each homework assignment on the link and returns:

  1. The assignment's name
  2. The assignment's permanent link
  3. The assignment's due date
  4. The assignment's solution link(s)
 
My crawler saves all of this data in the saved_data.csv file in the main directory. 
