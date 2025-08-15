# Yahoo API + Grok + Elasticsearch/Kibana

This project:
- Fetches current prices from the Yahoo Finance API.
- Parses and formats data using Logstash with Grok.
- Sends data to Elasticsearch for storage.
- Displays data in Kibana UI.

## Requirements
- Podman or Docker
- Elasticsearch
- Kibana
- Logstash
- GitHub account

## Setup Steps
1. Run Elasticsearch and Kibana in Podman.
2. Run Logstash container with mounted pipeline config.
3. Confirm Grok parsing works in Kibana.
4. Update the Yahoo API URL for your desired symbols.
