# ✨️ Vio's Portfolio

Welcome to my portfolio!

In here listed all of the projects I've tried my hands on. Check them out!

## 💻 Projects

Mostly data-related things

### Data Engineering

| Project | Completion Date | Tools | Description |
| --- | --- | --- | --- |
| [Coursera Data Warehouse for Business Intelligence Capstone][coursera-dwh] | June 2023 | Postgres, dbt, Looker | Finished the final part of [Coursera's Data Warehouse for Business Intelligence Specializations][coursera-dwh-bi] assignments and case studies involving modeling (Kimball-style), integration, query problems, and dashboard building |
| [Fluffy Folks Dashboard][ff-dashboard] | April 2023 | GraphQL API, sqlite, dbt, Streamlit, Airflow, Google Sheets | End-to-end pipeline of my online circle's anime and manga-related statistics. Initially built to address painful manual tracking and curation that a friend of mine did weekly. It includes a sheet and dashboard for user's access with 11 kinds of statistics. Sheets available online [here][ff-sheets] |
| [Anime and Manga Recommendation API][animanga-recommenders] | March 2023 | FastAPI, Docker | Deploying the recommendation model and association rules I've created on an API. Using best practices I've learned through various resource about how to best use [Docker for a Python deployment][docker-python] |
| [Caltech Data Engineering Exercises][caltech-de] | January 2023 | Postgres, MongoDB | Working through [Caltech Data Engineering][caltech-de-page] course exercises and case studies alongside the materials given |

### Machine Learning

| Project | Completion Date | Tools | Description |
| --- | --- | --- | --- |
| [Hackernews Topic Modeling][hackernews-topic-modeling] | November 2022 | SQL, asyncio, pandas, BERTopic | Extract [Hacker News][hn-link] public dataset served in BigQuery, performs data cleaning routine, and builds a topic model from the data. Curates personal browsing history to build user profile from the topic model that can be used for content-based recommendation |
| [MAL Favorites Association Rules][mal-fav-assoc] | February 2022 | pyspark | Uses Spark's [FP Growth algorithm][fp-growth] to mine user's favourites data to discover patterns and rules of favourites between each anime, manga, characters, and staff |
| [MAL Recommendation Model][mal-recsys] | November 2021 | pandas, Matplotlib, PyTorch, Spotlight | Build a [Matrix Factorization][mf-model] model that could be used as an engine for a recommendation systems that can recommend anime and manga for users. Trained using users' ratings data from MyAnimelist |

### Data Collection, Preparation and Analysis

| Project | Completion Date | Tools | Description |
| --- | --- | --- | --- |
| [Stratascratch Business Analysis][stratascratch-business-analysis] | June 2023 | pyspark, pandas, Matplotlib, H3, folium | A [data projects][stratascratch-data-projects-link] (case study) of analyzing reasons of failures for a corporate transportation management company. Answering business questions given in the task and doing the bonus task of visualizing where most failures happen in a map |
| [Tab Session Manager Deduplicator][tsmd] | October 2022 | pandas | Data cleaning and record deduplication of my [Tab Session Manager][tsm-repo] sessions, along with a little bit of fun exploration |
| [Skripsi Kawanku][skripsi-kawanku] | 2021 ~ | requests, bs4, Scrapy, Selenium, Tweepy, pandas, NLTK, scikit-learn, Matplotlib, seaborn | Helping some of my friends working through their bachelor's thesis; I get involved in various things in all phases of the data science lifecycle in many projects |
| [MAL Scraper and EDA][mals-scraper-eda] | 2021 | requests, bs4, pandas, Matplotlib | Collects users' profile information and ratings from MyAnimelist, run deduplication, clean the data to find sources of errors, and do EDA on the dataset |

### Languages

| Project | Completion Date | Tools | Description |
| --- | --- | --- | --- |
| [SQL Interview Preps][sql-interviews] | June 2023 ~ | SQL | Working through SQL exercises in various coding platforms (Hackerrank, Leetcode, Stratascratch), and other exercises I could find |
| [Scala Forth Exercism][scala-forth] | March 2023 | Scala | Implementing a simple subset of [Forth][forth-wiki], a stack-oriented programming language |
| [Scala Advent of Code][scala-aoc] | December 2022 | Scala | Working through [Advent of Code][aoc-link] 2022 problems (only made it through 14 days) |

[//]: # "| Codility | Coding Exercises | - | - | - |"
[//]: # "| Hackernews Topic Model Pipeline | Data Engineering | - | - | - |"

## 👯 Others

Non-data related things!

- [Fixing Vim Vixen extension bug (2022)](https://github.com/ueokande/vim-vixen)
- [Testing Notes (2021)](https://github.com/vioxcd/testing-notes)
- [React and Firebase E-Voting App (2019)](https://github.com/vioxcd/pemira_e-voting)
- [Plant Identification using AutoML (2019)](https://github.com/vioxcd/automl_plant_identification)
- [Personal shell scripts repository (2019 ~)](https://github.com/vioxcd/portfolio-guide/assets/31486724/bb5bdf39-17d0-4e9c-a7b0-7cade0a075bd)

---

This portfolio is inspired by [Katie Huang's Portfolio](https://github.com/katiehuangx/Portfolio-Guide)

[//]: # (Links)

[ff-dashboard]: https://github.com/vioxcd/ff-dashboard
[animanga-recommenders]: https://github.com/vioxcd/animanga-recommenders
[coursera-dwh]: https://github.com/vioxcd/coursera-dwh-for-bi-capstone
[hackernews-topic-modeling]: https://github.com/vioxcd/hackernews-topic-modeling
[tsmd]: https://github.com/vioxcd/tsmd
[scala-forth]: https://github.com/vioxcd/scala-forth-exercism
[scala-aoc]: https://github.com/vioxcd/aoc2022
[mal-recsys]: https://github.com/vioxcd/animanga-recommenders/blob/main/notebooks/Demo_CDRS.ipynb
[mal-fav-assoc]: https://github.com/vioxcd/animanga-recommenders/blob/main/notebooks/Spark_Association_Rules.ipynb
[sql-interviews]: https://github.com/vioxcd/sql-interviews-prep
[caltech-de]: https://github.com/vioxcd/caltech-de-exercises
[stratascratch-business-analysis]: https://colab.research.google.com/drive/1upxBM7mTrxvt-ftKFvla6IsBft9lk7cB?usp=sharing
[skripsi-kawanku]: https://github.com/vioxcd/skripsi-kawanku
[aoc-link]: https://en.wikipedia.org/wiki/Advent_of_Code
[tsm-repo]: https://github.com/sienori/Tab-Session-Manager
[hn-link]: https://news.ycombinator.com/
[fp-growth]: https://spark.apache.org/docs/latest/ml-frequent-pattern-mining.html
[mf-model]: https://en.wikipedia.org/wiki/Matrix_factorization_(recommender_systems)
[forth-wiki]: https://skilldrick.github.io/easyforth/
[docker-python]: https://docs.google.com/presentation/d/1yqSe1HUbs6qcEpN5Ck94LUDkIjAoTo29v8fLIqDjMBA/edit?usp=sharing
[caltech-de-page]: https://github.com/cal-data-eng/sp21
[coursera-dwh-bi]: https://www.coursera.org/specializations/data-warehousing
[ff-sheets]: https://docs.google.com/spreadsheets/d/1CUSfaHK2nlhUibzl5yADVuSef7hYPdTqOz4yGJSIE54
[stratascratch-data-projects-link]: https://platform.stratascratch.com/data-projects/insights-failed-orders
[mals-scraper-eda]: https://github.com/vioxcd/mals-scraper-eda

