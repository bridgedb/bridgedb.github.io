# Downloads

## Download the BridgeDb Java Library

The distribution can be downloaded from [this release folder](https://github.com/bridgedb/BridgeDb/releases).
There are two source distributions:

 * release-${version}.zip
 * release-${version}.tar.gz

A full archive can be found [at Zenodo](https://zenodo.org/record/593034).

Questions can be posted at the [BridgeDb mailing list](https://groups.google.com/g/bridgedb-discuss).

### Using the library in Maven, Gradle, etc

For Maven:

```xml
<dependencies>
    <dependency>
        <groupId>org.bridgedb</groupId>
        <artifactId>org.bridgedb.bio</artifactId>
        <version>3.0.21</version>
    </dependency>
</dependencies>
```

For Gradle:

```
compile group: 'org.bridgedb', name: 'org.bridgedb.bio', version: '3.0.21'
```

For Ivy:

```xml
<dependency org="org.bridgedb" name="org.bridgedb.bio" rev="3.0.21"/>
```

## Download the BridgeDb Identifier Mapping Databases

See the [overview of mapping databases](https://bridgedb.github.io/data/gene_database/).

## Using BridgeDb Webservice as a Docker container

See the [GitHub repository of the BridgeDb Docker](https://github.com/bridgedb/docker)
and the [DockerHub repository for BridgeDb](https://hub.docker.com/r/bigcatum/bridgedb/).
