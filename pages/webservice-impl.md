# Webservice Implementation

## Docker image
Our Webservice is also available as a Docker Image, for local deployment of the BridgeDb service and fast identifier mapping.
Find the instructions to pull and run the Docker Image at the bottom of this page. The BridgeDb Docker Images are hosted on [DockerHub](https://hub.docker.com/r/bigcatum/bridgedb/), where new Docker Images are stored after updated BridgeDb version or identifier mapping files by a GitHub action and Dockerfile on [Github repository](https://github.com/bridgedb/docker). All species covered in our [download list](https://bridgedb.github.io/data/gene_database/) are included in this docker.
[![docker stars](https://img.shields.io/docker/stars/bigcatum/bridgedb.svg?style=flat-square)](https://hub.docker.com/r/bigcatum/bridgedb)
[![docker pulls](https://img.shields.io/docker/pulls/bigcatum/bridgedb.svg?style=flat-square)](https://hub.docker.com/r/bigcatum/bridgedb)

### Instructions to pull and run the Docker Image

If you want to have the latest version of the Docker Image with the latest ID mapping files, use:

```shell
sudo docker pull bigcatum/bridgedb:latest
```
In case you want to have a specific version of BridgeDb, you can add the version as tag instead of "latest":

```shell
sudo docker pull bigcatum/bridgedb:3.0.21-2.1.3
```

Below is the command for running the Docker Image. In the command, change [PORT1] and [PORT2] to configure ports that are not yet in use in your system. If the ports 8183 and 8080 are not yet in use, you can simply use those for [PORT1] and [PORT2] respectively.
The environment variable [SERVER_URL] defines the host URL, depending on where the Docker Image will be run. If you do a local deployment, the [SERVER_URL] should be `http://localhost`, with the [PORT1] that you chose.

```shell
sudo docker run --name bridgedb --rm -p [PORT1]:8183 -p [PORT2]:8080 -e SERVER_URL='[SERVER_URL]:[PORT1]' bigcatum/bridgedb:latest
```
