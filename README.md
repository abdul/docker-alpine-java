# docker-alpine-java
An Alpine Linux based Docker Image that includes OpenJDK, and Maven. 

**Versions**
- Alpine 3.3 (gliderlabs/alpine:3.3)
- OpenJDK 7
- Maven 3.3.1


**Environment Variables**
- JAVA_HOME /usr/lib/jvm/java-1.7-openjdk
- JAVA=$JAVA_HOME/bin
- M2_HOME=/usr/lib/mvn
- M2=$M2_HOME/bin
- PATH $PATH:$JAVA_HOME:$JAVA:$M2_HOME:$M2


**Credits: Most of commands and configuration were taken from @vyo's repository - https://github.com/vyo/alpine-maven/. Thank you :-)**
