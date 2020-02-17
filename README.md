# Awesome Full Stack Data Science

Links to cool tutorials for cool technologies. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Full Stack Data Science](#awesome-full-stack-data-science)
  - [Code Quality](#code-quality)
  - [Code Optimisation](#code-optimisation)
  - [Reproducibility & Workflow Management](#reproducibility-workflow-management)
  - [Scalability](#scalability)
  - [API Deployment](#api-deployment)
  - [Cloud Services](#cloud-services)
  - [Deep Learning](#deep-learning)
  - [Viz & Dashboarding](#viz-dashboarding)
  - [CI / CD](#ci-cd)
  - [Database Setup & Frontend](#database-setup-frontend)
- [Resources](#resources)
- [Contributing](#contributing)

---

## Code Quality

- git
- pylint
- black
- [pytest](https://docs.pytest.org/en/latest/) - the unit testing framework
  - [un bon gros guide bien gras sur les tests unitaires en python, partie 3 (sam & max)](http://sametmax.com/un-gros-guide-bien-gras-sur-les-tests-unitaires-en-python-partie-3/) - why and how to use pytest (in french 🇫🇷)
- [hypothesis](https://hypothesis.readthedocs.io/en/latest/) - unit testing for data scientists
- [method chaining](https://en.wikipedia.org/wiki/Method_chaining) in pandas
  - [Modern Pandas (Part 2): Method Chaining (Tom Augspurger's blog)](https://tomaugspurger.github.io/method-chaining.html) - the original blog post explaining why & how to use method chaining in pandas
  - [The Unreasonable Effectiveness of Method Chaining in Pandas (towardsdatascience)](https://towardsdatascience.com/the-unreasonable-effectiveness-of-method-chaining-in-pandas-15c2109e3c69) - inspired by Tom Augspurger's post, post suggesting some clever utility functions to be used in method chaining with pandas

## Code Optimisation

- numba
- numpy
- multiprocessing

## Reproducibility & Workflow Management

- dvc
- mlflow
- [docker](https://www.docker.com/) - virtualization to deliver software in packages called containers
  - [docker for beginners (freecodecamp)](https://www.freecodecamp.org/news/a-beginners-guide-to-docker-how-to-create-your-first-docker-application-cc03de9b639f/) - how to create a docker application
  - [docker deeper dive (official doc)](https://docs.docker.com/get-started/)
    - Orientation and setup
    - Containerizing an application
    - Deploying to Kubernetes
    - Deploying to Swarm
    - Sharing images on Docker Hub
  - [docker-compose for beginners (freecodecamp)](https://www.freecodecamp.org/news/a-beginners-guide-to-docker-how-to-create-a-client-server-side-with-docker-compose-12c8cf0ae0aa/) - how to create a client/server side
  - [docker-compose manual (official doc)](https://docs.docker.com/compose/)

## Scalability

- spark
- dask
- rapids

## API Deployment

- APIs in general
  - [Utilisez des API REST dans vos projets web (openclassrooms)](https://openclassrooms.com/fr/courses/3449001-utilisez-des-api-rest-dans-vos-projets-web) - understand what an API is & learn how to use REST API (in french 🇫🇷)
- flask
- falcon

## Cloud Services

- AWS
- GCP
- Azure
- [cortex](https://www.cortex.dev/) - deploy machine learning models in production

## Deep Learning

- pytorch
- tensorflow

## Viz & Dashboarding

- kibana
- dash

## CI / CD

- gitlab
- github

## Database Setup & Frontend

 - NoSQL Database
   - [Choisissez votre famille NoSQL (openclassrooms)](https://openclassrooms.com/fr/courses/4462426-maitrisez-les-bases-de-donnees-nosql/4462433-choisissez-votre-famille-nosql) - understand the different nosql paradigms (key/value store, document store, column oriented vs row oriented, graph database) (in french 🇫🇷)
- postgresql/sqlite
- elasticsearch
  - [beginners tutorial on elasticsearch and kibana (openclassrooms)](https://openclassrooms.com/fr/courses/4462426-maitrisez-les-bases-de-donnees-nosql/4474691-etudiez-le-fonctionnement-d-elasticsearch) - understand the functioning of elasticsearch, how to set tup an ELS cluster and ingest data in command line, investigate data and create a simple dashboard with Kibana (in french 🇫🇷)
  - [Extract of Code Bank Data Engineering (gitlab - The Insighters)](https://gitlab.com/the_insighters/projects/codebankde/-/tree/sophie/src/ELK) - how to set up an ELS cluster with python, ingest data (and more...)


# Resources

- [The Missing Semester of Your CS Education (MIT)](https://missing.csail.mit.edu/) - Nice and simple courses from MIT to stop being a noob with a computer
- [The Book of Secret knowledge (github)](https://github.com/trimstray/the-book-of-secret-knowledge) - A collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools, and more
- [Tools and Products and Apps and ... for macOS (github)](https://github.com/jaywcjlove/awesome-mac)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://gitlab.com/the_insighters/awesome-full-stack-data-science/blob/master/CONTRIBUTING.md) first.
