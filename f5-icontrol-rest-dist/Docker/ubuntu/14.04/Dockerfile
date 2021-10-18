# Dockerfile
FROM ubuntu:trusty-20190515

RUN apt-get update && apt-get install -y \
	python-stdeb \
	fakeroot \
	python-all

COPY ./build-debs.sh /

