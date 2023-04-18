# A Hierarchical Constant-Score approach to construct Elasticsearch queries

This repo is to demonstrate some common challenges in applying Elasticsearch to solve site-search problems.

## How to start
- Starting Elasticsearch locally with docker-compose: `docker-compose up -d` ([ref](https://www.elastic.co/guide/en/elasticsearch/reference/8.6/docker.html#docker-compose-file))
- Go to Kibana at `localhost:5601`
- Login with the user and password in `.env` file
- Paste content in `scripts/queries.txt` into the Kibana Dev Console
- Clean up: `docker-compose down -v`