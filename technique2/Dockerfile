# run a simple container

#use an existing docker image as a base
FROM alpine

#download and install a dependency
RUN apk add --update redis

#communicate the process
CMD ["redis-server"]
