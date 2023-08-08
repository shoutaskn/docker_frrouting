FROM alpine
RUN apk update && apk add tcpdump
COPY startup.sh /tmp/startup.sh 
ENTRYPOINT ["/tmp/startup.sh"]
