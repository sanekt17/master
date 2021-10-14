FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd 
RUN apt-get -y install python-pip
RUN apk --purge -v del python-pip
CMD tail -f /dev/null

