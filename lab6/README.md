## Mongo DB Practice

The practice works in Docker using Docker Compose.

First of all, watch the video below.

[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://youtu.be/YV2ZPLjlnlA)

Second, if your are not familiar with MongoDB, make yourself at easy following the [Practice.ipynb]([<Practice.ipynb>](http://localhost:8888/notebooks/work/data/Practice.ipynb) Notebook.

Once complete (or right away if you feel confident about MongoDB), complete the [Homework.ipynb](http://localhost:8888/notebooks/work/data/Homework.ipynb) Notebook.

## Pedagogical Objectives:

- Refreshing your knowledge of MongoDB
- Understand how Document Store represent data, and their difference with relational data

## How to Run

You can run it either Locally (as we saw in the docker lecture) or with [Github Codespace](https://30daysof.github.io/data-science-day/week-2/1-codespaces/)

### Locally

- run ```docker compose up``
  - you can use Visualstudio Code
  - you can use a dockerised installation of Jupyter
  - in the compose there is also a mongo express client container to visualise the content of the database. Accessible locally on port 8081
  
### CodeSpace

Open Codespace as indicated in the images below (use the main branch).
And run docker in the codespace. From here on is the same as locally.

![codespaces](../codespaces-howto.png)

![visualstudio](figs/codespaces-visualstudio.png)

### Good to know (MongoDB in the Cloud ([Mongo-Atlas](https://docs.atlas.mongodb.com/getting-started/)))

- If you are using MongoDB in the Cloud (Atlas), you will need to:
    - [Create an Atlas Account and Cluster](https://docs.atlas.mongodb.com/getting-started/)
    - [Set Up Connectivity to Atlas](https://docs.mongodb.com/guides/cloud/connectionstring/)
