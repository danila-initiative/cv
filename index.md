# Danila Avramenko  
Male, 31 years old

+7 925 487 64 09 (Telegram, WhatsApp)  
danila.avramenko@gmail.com   
<a href="https://www.linkedin.com/in/danila-avramenko-77912ab9/" target="_blank">LinkedIn</a>  


Residence: Montenegro.   
Ready to relocate, ready for business trips.

___
## Skills
Experienced metal forming engineer, naturally converted into a programmer.  

Key engineering skills: FEM simulation, Forging, Ring Rolling, Rolling, Technology design, Technology optimization, CAD systems, Technical support

Key programming skills: Python, REST API, Git, ML, C++, Docker, Postgresql, SQLite3, Flask, MongoDB, Telegram bots, Graphana, Kibana, Agile, Scrum

___
## Experience

**Backend Python developer @ [Yandex Eats](https://www.wikiwand.com/en/Yandex_Eda)** <br>
_Moscow, Russia (July 2021 - Present)_ <br>
- Developing microservices using Python,  C++ (if really necessary 😊), and utilizing YAML for configuration.
- Writing tests using pytest and gtest.
- Designing APIs and specifying endpoints with OpenAPI.
- Creating monitoring and alerting systems.
- Developing an automated system to efficiently and accurately respond to specific user support requests.



**Software Developer @ [QuantorForm](https://www.linkedin.com/company/quantor-form/about/)** <br>
_Moscow, Russia (October 2020 - July 2021)_ <br>
- Development of the Ring rolling and Rolling modules (C++)
- Elaboration of development's direction of Rolling and Ring rolling modules



**Technical support Engineer @ [QuantorForm](https://www.linkedin.com/company/quantor-form/about/)** <br>
_Moscow, Russia (October 2015 - October 2020)_ <br>
- Finite element simulation of different metal forming technologies: the Open die forging, the Closed die forging, the Ring rolling, the Longitudinal rolling, the Cross rolling, the Rotary forging, the Extrusion, and the Wheel rolling.
- Conducting training worldwide in the simulation of specific metal-forming technologies.
- Product development of new functionality and interface development.
- Development of automated testing software using API (Python).
- Development of documentation.
- Design and optimization of various forging processes.
- Preparing and conducting presentations of the company’s products and new software versions.
- Providing technical support to customers with a focus on ring rolling and rolling processes.


___
## Education
**Bauman Moscow State Technical University** <br>
_Moscow, Russia (September 2008 - June 2014)_ <br>
- Master’s Degree in Mechanical Engineering
- Metall Forming Technology


___
## Pet Projects
**[2022] Finding memes by string. Telegram bot**  

This bot helped users to search for images (memes) by entering keywords. The stack included `imagehash` for images (memes) deduplication, with hash type and hash size selected experimentally, `Tesseract` for text recognition (multiple languages simultaneously), and `Elasticsearch`, a search engine and database that contains image hashes, recognized and processed text.

For the minimum viable product, I created a Telegram bot hosted locally and a static database of 13,000 memes. I tested its functionality with my friends. However, I decided to change the project architecture in order to make the bot work perfectly and add automatic continuous enrichment of the memes database. The project is on hold now 🙂.


<br>

**[2022] Order readiness notification. Telegram bot**  

The Bot for Bar Zionist in Moscow was developed to address the issue of people not knowing when to pick up their food from the counter in the food court system. The process involved clients placing their food order at the counter and returning several times until their food was ready. It was easy to launch this bot because the co-owner of the bar is my friend.

There are actually two bots - one for guests and one for chefs - that share the same database in a JSON file 🙂. This file contains orders and telegram IDs to send notifications. I chose to use a JSON file because the bot usage numbers are from 10 to 200 times a day.

To use the bot, guests send their order number to the bot, and when the order is ready, the chef presses a button on a special keyboard with order numbers. The guest then receives a notification in different languages, wishing them "bon appetit".

This is a straightforward and simple solution that is useful for me, my friends, and other bar guests.

<br>

**[2022] Site parsing by specified parameters. Telegram bot**   

The purpose of my pet project was to develop a bot that sends search results every weekday via a message containing statistics (number of search results) and an excel table with actual results.

To set the source data for the search, was implemented a finite state machine, and after the test period, was added a subscription option using the Telegram-supported payment service, Yookassa.

Was used the `aiogram` and `beautifulsoup` libraries, and `SQLite3` were used for the database. Most of the code has type hinting. I developed and deployed the bot using `Docker`, the `Makefile` was used to run frequent commands like tests, linters (flake8, mypy), formatter (black).

For each test, was created a clean DB with all actual migrations and filled with data if necessary. I also set up Crons for site parsing, saving results in DB, saving results from DB into excel tables, and forming messages to send the results.

The bot was deployed on DigitalOcean and tested for three weeks with five familiar users. However, the bot lost relevance after that.

<br>

**[2020] Pet projects for inner usage of QuantorForm**  

1. **Service for mechanical properties (flow stress) of steel generation**: This service generates flow stress curves of steel based on the chemical composition of the steel. The service was developed in several steps, including collecting and processing data, training a regression model, and creating a service on Flask that can generate graphs and tables with data. The service is used by two plants on a daily basis.

2. **Search service for materials by name and chemical composition**: This is a search service that helps people find needed material based on name or on chemical composition. The service has a special algorithm that takes into account the specific names of materials for different standards. This service has been particularly helpful to the technical support department in resolving customer requests.

<img src="service.jpg" alt="drawing" width="400"/> <br>

<br>

___
## Languages

Russian (native), English (advanced) <br>