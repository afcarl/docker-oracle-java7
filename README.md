docker-oracle-java7
===================

Docker file for Debian with Oracle 7

Based on [akisei's oracle-java7](https://github.com/akisei/dockerfiles/blob/master/oracle-java7/Dockerfile), which in turn is based on the [WebUpd8 instructions](http://www.webupd8.org/2012/01/install-oracle-java-jdk-7-in-ubuntu-via.html).
I added some DEBIAN_FRONTEND settings to reduce red output during the build, and added `oracle-java7-set-default`.

This repository triggers the [makuk66/docker-oracle-java7](https://index.docker.io/u/makuk66/docker-oracle-java7/) trusted build on the Docker index. 
