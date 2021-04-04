FROM ubuntu:14.04
RUN mkdir /tmp/warnik && \
apt-get update && \
apt-get install maven git -y && \
git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git /tmp/boxfuse
WORKDIR /tmp/boxfuse
CMD mvn package && cp ./target/hello-1.0.war /tmp/warnik/hello.war
