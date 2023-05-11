# Webservice Implementation

## Docker image
Our Webservice is also available as a Docker image, for local fast querying.
Find the instructions to pull the docker image at the bottom of this page.
[![docker stars](https://img.shields.io/docker/stars/bigcatum/bridgedb.svg?style=flat-square)](https://hub.docker.com/r/bigcatum/bridgedb)
[![docker pulls](https://img.shields.io/docker/pulls/bigcatum/bridgedb.svg?style=flat-square)](https://hub.docker.com/r/bigcatum/bridgedb)

## Shiny App
Our Webservice is used in a new [RShiny app](https://shiny.bridgedb.org), which also includes mappings for outdated identifiers.

![image](https://github.com/bridgedb/bridgedb.github.io/assets/26277832/22426d90-0dec-4b20-8b7f-67d7a85ccca3)

## BridgeDb webservice as docker image for OpenRiskNet

The BridgeDb webservice is available from [Docker hub](https://hub.docker.com/r/bigcatum/bridgedb/)
for version control and [Github repository](https://github.com/bridgedb/docker) with build configuration
steps. All species covered in our [download list](https://bridgedb.github.io/data/gene_database/) are included in this docker.



![OpenRiskNet logo](../images/OpenRiskNetlogo_simSizeOpenPhacts.png)

### Instructions to pull the Docker Image

Installation:

```shell
docker pull bigcatum/bridgedb
```

Run:

```shell
sudo docker run -p 8183:8183 bigcatum/bridgedb
```
