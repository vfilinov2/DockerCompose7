FROM jetty:9.4.39-jre11-slim

CMD /usr/local/openjdk-11/bin/java -Djetty.home=/usr/local/jetty -Djetty.base=/var/lib/jetty -Djava.io.tmpdir=/tmp/jetty \
-jar /usr/local/jetty/start.jar jetty.state=/var/lib/jetty/jetty.state jetty-started.xml


