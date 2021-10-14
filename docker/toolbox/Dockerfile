FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python-pip
RUN pip install awscli
RUN apk --purge -v del python-pip
CMD tail -f /dev/null

