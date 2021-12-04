<img src='https://user-images.githubusercontent.com/1423657/99822833-f9504780-2b53-11eb-8b28-99484eab6157.png' width=250>

## [cLoki](https://github.com/lmangani/cLoki) Canary

Loki Canary is a standalone app that audits the log-capturing performance of a Grafana Loki cluster.

This docker compose bundle will spin up a cLoki + Clickhouse instance running the Loki Canary agent.

<img src="https://grafana.com/docs/loki/latest/operations/loki-canary-block.png" width=500 />

#### THIS EXAMPLE IS INTENDED FOR TESTING PURPOSES!

## Components

#### Core
* cLoki [yml](https://github.com/metrico/cloki-docker-canary/blob/main/cloki.yml)
* clickhouse-server [yml](https://github.com/metrico/cloki-docker-canary/blob/main/clickhouse-service.yml)
#### Add-Ons
* loki-canary
  * pastash 
  * promtail

### Setup

```bash
docker-compose up
```

#### Usage

* Watch the canary output for details

