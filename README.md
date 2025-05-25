# vector

## Setup
* https://vector.dev/docs/setup/installation/package-managers/apt/
* sudo systemctl enable vector
* sudo systemctl start vector

## Configuration
* [vector.yaml
](https://github.com/ariniemi/vector/blob/main/vector.yaml)

## Authentication
* Configured in Grafana Cloud console: https://grafana.com/orgs/nnnn
  * I.e. not congifured in the Grafana instance: https://nnnn.grafana.net 
* Check Loki/Send Logs to find the URL and username
* Set token/password in Access Policies
