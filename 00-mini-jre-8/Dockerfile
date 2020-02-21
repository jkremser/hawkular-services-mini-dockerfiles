FROM alpine:3.4
#RUN apk --update --no-cache add openjdk8-jre=8.111.14-r0 --repository=http://dl-cdn.alpinelinux.org/alpine/v3.4/community && rm -rf /var/cache/apk/*
RUN apk --update --no-cache add openjdk8-jre && rm -rf /var/cache/apk/* && rm -rf /var/cache/apk/* && rm -rf /usr/lib/libX11* /usr/lib/libp11* /usr/lib/libasound* /usr/lib/libsqlite* /usr/lib/jvm/java-1.8-openjdk/jre/lib/ext/{cldrdata,nashorn}.jar
ENV JAVA_HOME /usr/lib/jvm/default-jvm
CMD ["/usr/bin/java", "-version"]
