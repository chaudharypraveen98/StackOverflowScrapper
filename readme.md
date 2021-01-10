## **Stack Overflow Question Scrapper**
This scrapper scrapes the questions from the stack overflow depending upon the number of votes, newest, active , no of question, no of pages to search and the field in which you want to search the question(topic).

##### Level: Beginner

##### Requirements:-
1. Request-html
2. Pandas
3. Request library

##### How to use :-
1. First clone the repo by following command:-
<br>`git clone https://github.com/chaudharypraveen98/StackOverflowScrapper.git`
2. Then you have to install all the required dependencies by following command :-
`pip3 install -r requirements.txt`
3. Run the file in python interactive mode. Now you are ready to go. To scrap the Stack Overflows Question , type:- <br>
`scrape_stack(tag="python", page=1, pagesize="20", sortby="votes")`
<br>where
<br>**_tag_**: Field you want to search like c, javascript, html etc.
<br>**_page_**:How many pages you want to search.
<br>**_pagesize_**: How much questions or thread each page contains.
<br>**_sortby_**: You can sort the question according to votes,newest,active and unanswered.

_**Note**_: Any changes are most welcomed. By default the file extension is set to CSV with the tag you used for scraping
