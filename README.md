# docker-sbt

Docker image that embeds
 * a JDK 8
 * a SBT instance

The image is build using:

        $ docker build -t bdorville/sbt:0.13.12

# docker-sbt-node

Docker images that embeds
 * a JDK 8
 * a SBT instance

The images are build from the root of the repository using:

    $ docker build -t bdorville/sbt-node:0.13.12-6.4.0 sbt-node
    $ docker build -t bdorville/sbt:0.13.12-jdk-8 sbt-jdk-8

