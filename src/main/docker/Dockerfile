FROM java:8
EXPOSE 80

RUN mkdir -p /usr/upload/

VOLUME /usr/upload/

ADD run.sh /run.sh

RUN chmod +x /run.sh

ADD basic-*.jar /basic.jar

ENTRYPOINT sh /run.sh