# Case study of using Docker to create a data engineering architecture

## Features

- Airflow as scheduler
- Airbyte as ingestion tool
- Spark as processing tool
- MySql as data source
- Postgres as data warehouse
---
## Architecture

![](./architecture.png)

---
## Installation

You need [Docker](https://www.docker.com/) to run the data stack.

To run the data stack you just need to:
```sh
docker compose --profile profilenameincmopose up -d
```


