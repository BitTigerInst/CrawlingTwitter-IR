# CrawlingTwitter-IR
only for Unicorn(外省青年)

# AraChat

Description
-----------

Inspired by an information retrieval project. Find the right answerers for twitter question. But this time, we want to improve this project. Crawling twitter through Twitter API has some limitations. So we want to using Scrapy and store the tweets into MongoDB or Neo4j. And do some IR jobs or sensitive analysis on the text


Plan
----

Based on our experiences on web development and descriptions metioned above, we take _Feb, 2016_ as the __1st stage__ with the __primary__ goal of __prototyping__ our own chat application following the [Development Guildlines](https://github.com/BitTigerNY/AraChat/edit/master/README.md#Development Guildlines) metioned below. Here're some tentative schedules.

* __[2016/02/01 - 2016/02/07]__ Project Selection, Plan Discussion, and Proposal Draft Writing
* __[2016/02/08 - 2016/02/24]__ System Design, Resource Discovery, Project Implementation, Document Writing 
* __[2016/02/25 - 2016/02/29]__ User Manual Writing and Video Presentation Making

_Details of each schedule and task will be added later._

Resource
--------

1. __[BitTiger Project: AppStore - Crawler]__ https://slack-files.com/T0GUEMKEZ-F0J4G9QTT-274d3bc97e
2. __Scrapy Documentation [http://doc.scrapy.org/en/0.20/]

Language & Framework
--------------------

Python, MongoDB, Twitter API, Neo4j

Development Guildlines
----------------------

- __Modularity.__ Following the principle _"loose coupling and high cohesion"_, each module should be standalone.

- __Minimalism.__ Each module should be kept short, simple, and concise. Every piece of code should be transparent upon first reading. 
- __Easy extensibility.__ New modules (as new classes and functions) are should be simply add, and existing modules should be extended easily.

Owner
-----

@team: Unicorn
