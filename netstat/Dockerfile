# Run the netstat command for network related information. 

# docker run --rm --name netstat -it \
# --pid host \
# omegazyadav/netstat

FROM alpine:latest

MAINTAINER "Yadav Lamichhane <omegazyadav1@gmail.com> "

RUN apk add --update net-tools

CMD ["netstat","-tulpn"]

