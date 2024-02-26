# Danila Avramenko
danila.avramenko@gmail.com
<a href="https://www.linkedin.com/in/danila-avramenko-77912ab9/" target="_blank">LinkedIn</a>

Residence: Montenegro.
Ready to relocate, ready for business trips.

<br>

# Summary
I am a backend developer with 3 years of experience in development and 6 years as a simulation engineer.

My main languages are `Python` and `C++`, and I specialize in web projects. I have worked in a small company (~30 people) and in large big tech (26k+ people). I realized, that I prefer small and mid-size companies, where I can see the result of my work, have a direct impact on the product and wider range of responsibilities.

I have a good communication skill and I think that good communication and collaboration is a key to successful project.

I like to keep my projects as simple as possible at each step of development. I believe that all great products evolved from simple MVPs.

<br>

# Skills

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=for-the-badge&logo=Airtable&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green) ![Obsidian](https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white) ![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
<br>

Other skills without cool badges: `pytest`, `gtest`, `CI/CD`, `REST API`, `OpenAPI`, `JSON`, `Copilot`, `Telegram bots`, `FEM simulation`, `CAD`, `Forging`, `Ring Rolling`, `Rolling`, `Technology design`, `Technology optimization`

<br>

# Experience

## Backend Python developer @ [Yandex Eats](https://eats.yandex.com/?lang=en) 
_(July 2021 - Present)_ 
Yandex Eats - online food ordering and delivery platform launched by Yandex in 2018. 200k+ orders per day.
- I maintained and developed the complex process of hiring couriers. I improved stability in the registration process, added a monitoring and alerting system. I added integration with external courier providers.
- I led the project to enhance courier support. When couriers contacted technical support during an order, the technical support employees automatically had all the necessary information about the order to provide better assistance in the situation.
- Currently, I am focused on optimizing the order flow and working on projects that aim to simplify the work of couriers.
- Developing microservices using `Python`, `C++`, and utilizing YAML for configuration.

## Software Developer @ [QuantorForm](https://www.linkedin.com/company/quantor-form/about/) 
_(October 2020 - July 2021)_ 
QForm - engineering software used for simulation, analysis and optimization of metal forming processes.
- Spearheaded the enhancement of the `Ring Rolling` and `Rolling` modules.
- Formulated and refined the development trajectory for both Rolling and Ring Rolling modules.

## Technical support Engineer @ [QuantorForm](https://www.linkedin.com/company/quantor-form/about/) 
_(October 2015 - October 2020)_ 
- Conducted over 70 training worldwide in the simulation of specific metal-forming technologies.
- Developed an automated testing system using API.
- Prepared and conducted over 20 webinars on the company's products.
- Made a simulation of the following processes: Open die forging, Closed die forging, Ring rolling, Longitudinal rolling, Cross rolling, Rotary forging, Extrusion, and Wheel rolling.
- Described and suggested improvements in `Rolling` and `Ring rolling` modules that were subsequently implemented: automatization of setting the initial parameters for simulation and special boundary conditions.
- Developed documentation for the `Ring Rolling` module.

<br>

# Education
## Bauman Moscow State Technical University
_(September 2008 - June 2014)_ 
- Master’s Degree in Mechanical Engineering
- Metall Forming Technology

<br>

# Pet Projects
## [2020] Pet projects for inner usage of QuantorForm
_Works now_  
**Result of the project**: Saved **hundreds of hours** of work for the technical support department and improved the quality of the support provided to customers.

The technical support department has received many requests from customers searching for a material model for simulation. We spent a lot of time searching for the required material model (QForm did not have a search engine for materials). Consequently, I created two services that are still used by the company:
1. Service for **mechanical properties (flow stress) of steel generation**: This service generates flow stress curves of steel based on the chemical composition of the steel. The service was developed in several steps, including collecting and processing data, training a regression model, and creating a Flask-based service that can generate graphs and tables with data.
2. Search service for materials by name and chemical composition.

## [2023] Finding memes by string. Telegram bot

_Works now_  
https://t.me/meme_initiative_bot

This bot helped users to find memes by entering keywords. The stack included `imagehash` for images (memes) deduplication, with hash type and hash size selected experimentally, `Tesseract` for text recognition (multiple languages simultaneously), and `Elasticsearch`, a search engine and database that contains image hashes, recognized and processed text. Memes base contains 60k+ memes.

## [2022] Order readiness notification. Telegram bot
_Works now_  
**Result of the project**: Bot notified about readiness of 20k+ orders, saved 20k+ minutes of wasted waiting time for guests.

The Bot for Bar Zionist was developed to address the issue of people not knowing when to pick up their food from the counter in the food court system. The process involved clients placing their food order at the counter and returning several times until their food was ready.

There are two bots - one for guests and one for chefs - that share the same database in a JSON file 🙂. This file contains orders and telegram IDs to send notifications. I chose to use a JSON file because the bot usage numbers are from 10 to 200 times a day.

This is a straightforward and simple solution that is useful for me, my friends, and other bar guests.

<br>

# Languages
Russian (native), English (upper intermediate)