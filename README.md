# Java Docker by onstructive GmbH

This repository provides you custom Java Docker images based on OpenJDK. All images extend the OpenJDK image by

- adding `curl` to the image to perform health checks.
- setting the timezone to `Europe/Zurich`

You will find all images at [Docker Hub](https://hub.docker.com/r/onstructive/java).

## Docker Image Tag

The tags of the Docker images have the following format:

     <openjdk tag>-<datestamp>-<timestamp>

Here is an example of the JRE 11 image

     11.0.10-jre-slim-buster-20210207-2103
