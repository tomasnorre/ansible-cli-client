FROM alpine:3

RUN apk add --no-cache ansible
#RUN pip3 install ansible

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
