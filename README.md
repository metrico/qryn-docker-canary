<img src='https://user-images.githubusercontent.com/1423657/147935343-598c7dfd-1412-4bad-9ac6-636994810443.png' style="margin-left:-10px" width=220>

## [cLoki](https://github.com/lmangani/cLoki) [Canary](https://grafana.com/docs/loki/latest/operations/loki-canary/)

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

![image](https://user-images.githubusercontent.com/1423657/144712701-19506523-5f34-4e46-b813-a5228fad9032.png)

<!--
![image](https://user-images.githubusercontent.com/1423657/144712675-5111209e-0511-4203-8fbd-466def03cefb.png)
-->
