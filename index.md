# Danila Avramenko
<img src="user_pic.jpg" alt="drawing" width="200"/>

_Middle Backed developer_ <br>

[Email](mailto:kuavramenko@gmail.com) / [LinkedIn](https://www.linkedin.com/in/danila-avramenko-77912ab9/)

___
## Skills
Experienced metall forming engineer, naturally converted into programmer.
Key technologies stack: Python, REST API, Git, ML, C++, Docker, Postgresql, SQLite3, MongoDB, Telegram bots, Graphana, Kibana, Flask, Agile, Scrum, CAD systems

___
## Languages

Russian (native), English <br>

___
## Experience

**Backend Python developer @ [Yandex Eats](https://www.wikiwand.com/en/Yandex_Eda)** <br>
_Moscow, Russia (July 2020 - Present)_ <br>
- Development of microservices on Python, C++ (if really necessary) and of course on yaml 😊
- Writing tests by using pytest and gtest
- API designs and endpoints specification (OpenAPI)
- Creation of monitorings and alerting



**Software Developer @ [QuantorForm](https://www.linkedin.com/company/quantor-form/about/)** <br>
_Moscow, Russia (October 2020 - July 2021)_ <br>
- Development of the Ring rolling and Rolling modules (C++)
- Elaboration of the direction of development of Rolling and Ring rolling modules



**Engineer @ [QuantorForm](https://www.linkedin.com/company/quantor-form/about/)** <br>
_Moscow, Russia (October 2015 - October 2020)_ <br>
- Finite element simulation of different metal forming technologies
- Conducting of metal forming technologies simulation training worldwide
- Product development of new functionality; interface development
- Development of automated testing of software by using API (Python)
- Documentation development
- Design of a variety of forging processes
- Optimization of a variety of forging technologies

___
## Education
**Bauman Moscow State Technical University** <br>
_Moscow, Russia (September 2008 - June 2014)_ <br>

- Master’s Degree in Mechanical Engineering
- Metall Forming Technology

___
## Additional
**Telegram bot for site parsing by specified parameters (2022)** <br>
Bot sends search results every weekday: a message with statistics on results + excel table with results.

Was implemented finite state machine to set the source data for search. 
The possibility of paying for a subscription after the test period was implemented. For payments was using one of payment acceptance service supported by the Telegram (yookassa). 

Base libraries: aiogram, beautifulsoup. DB: SQLite3. Most of code with type hinting. Development and deployment using Docker. Makefile to run frequent commands: tests, linters (flake8, mypy), formatter (black), rebuilding and entering into the container. For each test clean DB is created. DB with all actual migrations and filling with data for each test individually if necessary. Crons: site parsing + saving results in DB; saving results from DB into excel tables; messages formation and sending the results.


**Pet projects for inner usage of QuantorForm (2020)** <br>
1. Service for generation of mechanical properties (flow stress) of steel by chemical composition (an original approach to the problem).  
Formulation of an idea -> formalization of a task -> data collection -> data processing -> training of a regression model (Catboost) -> development of a service on Flask (drawing graphs small amount of JS)

2. Search service for materials by name and chemical composition.  
Has written search algorithm taking into account the specifics of the name of the materials for various standards.

<img src="service.jpg" alt="drawing" width="400"/> <br>
