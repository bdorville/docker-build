# docker-sbt

Docker image that embeds
 * a JDK 8
 * a SBT instance

## Building

The image is build using (from the root of the repository):

    $ docker build -t bdorville/sbt:1.0.0-jdk-8 sbt-jdk-8

## Pushing

Once the image is successfully built, it can be pushed to the Docker Hub:

    $ docker push bdorville/sbt:1.0.0-jdk-8

# docker-sbt-node

Docker images that embeds
 * a JDK 8
 * a SBT instance

## Building

The images is build using (from the root of the repository):

    $ docker build -t bdorville/sbt-node:1.0.0-8.4.0 sbt-node

## Pushing

Once the images is successfully built, it can be pushed to the Docker Hub:

    $ docker push bdorville/sbt-node:1.0.0-8.4.0

