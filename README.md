# Grafana

Docker Compose configuration file for Grafana, ready to use

This example shows how to use Grafana to visualize the data from MongoDB.

## Prerequisites

- Usage of `jwilder/nginx-proxy`
- existing docker networks `auto-reverse-proxy-global-network` and `mongodb_service-network`

## How to run

in order to use other data source, you need to add the corresponding network

# Credits
Inspired by [this](https://medium.com/swlh/easy-grafana-and-docker-compose-setup-d0f6f9fcec13)
and [this](https://hub.docker.com/r/grafana/grafana-oss)
and [this](https://stackoverflow.com/questions/54039604/what-is-the-default-username-and-password-for-grafana-login-page)