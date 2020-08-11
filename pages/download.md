# Downloads

## Download the Java Library

The distribution can be downloaded from [this release folder](https://github.com/bridgedb/BridgeDb/releases).
There are two source distributions:

 * release-${version}.zip
 * release-${version}.tar.gz

A full archive can be found [at Zenodo](https://zenodo.org/record/593034).

### Using the library in Maven, Gradle, etc

For Maven:

```xml
<dependencies>
    <dependency>
        <groupId>org.bridgedb</groupId>
        <artifactId>org.bridgedb.bio</artifactId>
        <version>2.3.5</version>
    </dependency>
</dependencies>
```

For Gradle:

```
compile group: 'org.bridgedb', name: 'org.bridgedb.bio', version: '2.3.5'
```

For Ivy:

```xml
<dependency org="org.bridgedb" name="org.bridgedb.bio" rev="2.3.5"/>
```

## Download the Identifier Mapping Databases

See the [overview of mapping databases](mappingdbs.md).

## Using BridgeDb as a Docker container

See the [GitHub repository of the BridgeDb Docker](https://web.archive.org/web/20190824104419/https://github.com/bridgedb/docker)
and the [DockerHub repository for BridgeDb](https://web.archive.org/web/20190824104419/https://hub.docker.com/r/bigcatum/bridgedb/).

Deployment files for OpenShift are [available here](https://web.archive.org/web/20190824104419/https://github.com/OpenRiskNet/home/tree/master/openshift/deployments/bridgedb).
Also, BridgeDb is directly available in the OpenShift catalog of the OpenRiskNet project.

