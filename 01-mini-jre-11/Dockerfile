FROM alpine:3.11
RUN apk --update --no-cache add openjdk11-jre --repository=http://dl-cdn.alpinelinux.org/alpine/edge/community && rm -rf /var/cache/apk/* && rm -rf /usr/lib/libX11* /usr/lib/libp11* /usr/lib/libasound* /usr/lib/libsqlite*
ENV JAVA_HOME /usr/lib/jvm/default-jvm
CMD ["/usr/bin/java", "-version"]
