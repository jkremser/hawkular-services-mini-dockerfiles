FROM alpine:3.8
RUN apk --update --no-cache add openjdk8-jre && rm -rf /var/cache/apk/* && rm -rf /usr/lib/libX11* /usr/lib/libp11* /usr/lib/libasound* /usr/lib/libsqlite* /usr/lib/jvm/java-1.8-openjdk/jre/lib/ext/{cldrdata,nashorn}.jar
ENV JAVA_HOME /usr/lib/jvm/default-jvm
CMD ["/usr/bin/java", "-version"]
