# news_scrapping_notification_updates

The objective is to build an application which enables an automation mechanism that triggers alerts when there are updates within our tracking websites, 
notification pages like NEET(nta.ac.in), SSC (ssc.nic.in) etc. and News websites like Shiksha, NDTV, Timesnow, Mint, Indian express, Hindustan times.

Techniques used:
  Category website scraping:Python Beautifulsoup
  Google News and Trends scrapping: Python packages
  Trigger platforms: Gmail, Whatsapp, Slack

Steps & Process:
Category website scraping:
SSC Category:
    Following is the SSC notification page: https://ssc.nic.in/Portal/Notices.
    There are 9 different tabs which show notification updates within different SSC sub-categories.
The application built will scrape content through each tab and tables within, check if the website is updated for the particular run date then scrape the actual content and trigger it to respective teams.

For ex: When this particular page of the SSC tab is updated,

Our application triggers the following output through email automatically. The same process is replicated through Whatsapp group and Slack channel.

2.NEET website scraping:
The above steps have been enabled for  https://nta.ac.in/NoticeBoardArchive website as well.

3. News website scraping:
https://www.shiksha.com/news
https://www.ndtv.com/education/exams-news


