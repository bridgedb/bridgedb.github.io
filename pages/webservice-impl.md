# Webservice Implementation

![OpenRiskNet logo](OpenRiskNetlogo_simSizeOpenPhacts.png)

## BridgeDb webservice as docker image for OpenRiskNet

The BridgeDb webservice is available as
[docker image](http://bridgedb.prod.openrisknet.org/swagger/)
in the [OpenRiskNet e-infrastructure](https://home.prod.openrisknet.org/) containing
mapping files for metabolites, and gene mapping files for Homo sapiens, Mus musculus and Rattus
norvegicus. Link to the [Docker hub](https://hub.docker.com/r/bigcatum/bridgedb/)
for version control and [Github repository](https://github.com/bridgedb/docker) with build configuration
steps.

### Instructions to pull the Docker Image

Installation:

```shell
docker pull bigcatum/bridgedb
```

Run:

```shell
sudo docker run -p 8183:8183 bigcatum/bridgedb
```
