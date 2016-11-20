FROM java:openjdk-8

ENV SBT_VERSION 0.13.13

RUN mkdir -p /usr/share/sbt && \
    curl -kfsSL https://dl.bintray.com/sbt/native-packages/sbt/$SBT_VERSION/sbt-$SBT_VERSION.tgz \
    | tar -xzC /usr/share/sbt --strip-components=1 && \
    ln -s /usr/share/sbt/bin/sbt /usr/bin/sbt

ENV SBT_HOME /usr/share/sbt

VOLUME /root/.sbt

CMD ["sbt"]
