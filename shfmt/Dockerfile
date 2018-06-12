FROM golang:alpine
MAINTAINER Odin Ugedal <odin@ugedal.com>
RUN	apk add --no-cache --virtual deps git \
	&& go get -u mvdan.cc/sh/cmd/shfmt \
	&& apk del deps
