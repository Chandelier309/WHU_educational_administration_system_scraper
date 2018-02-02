# School_system_scraper

武大教务系统Python爬虫

## Description
一个针对[武汉大学教务系统](210.42.121.132)的Python网络爬虫:包括专业课爬虫,公选课爬虫

A web crawler written by python for Wuhan University's educational adminitration system: including professional courses crawler, elective courses crawler

## How-to
source code for professional courses crawler, courses crawler are respectively: professional_courses_scraper.py, optional_courses_scraper.py 

You can simply run them on your computer through python 3.5+

professional_courses_scraper.py is based on Selenium and Chromedriver; while optional_courses_scraper.py is directly achieved by the package: request.

Beautifulsoup is not used.

# Requirements
First of all, you need a valid account, i.e., a user id for Wuhan University's educational adminitration system.

Second, you ought to install Python dependencies required by those python code:
* packages like xlwt, selenium. 
* [Chromedriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)
* [Chrome](https://www.google.com/chrome/browser/desktop/index.html)
* [Phantomjs](http://phantomjs.org/download.html)
