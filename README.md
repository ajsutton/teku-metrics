# Teku With Metrics

This is a docker-compose setup with Teku, Prometheus and Grafana connected to the Schelsi testnet.

It's not intended to be a generic solution and parts will obviously be specific to my particular
config but may be a useful example or starting point for others.

*WARNING:* There are a number of ports left open and many default passwords used. Do not expose this
to any untrusted network. I would also not recommend this particular setup for anything with real 
ETH. It's just a quick little setup for playing around with.

### URLs

Grafana will be available at http://localhost:3000/

The Teku REST API will be available at http://localhost:8545/