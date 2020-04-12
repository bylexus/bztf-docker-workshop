FROM ubuntu:18.04

RUN apt-get update && apt-get dist-upgrade -y
RUN apt-get install -y cmake make gcc g++

COPY example.cpp /src/example.cpp

WORKDIR /src

CMD g++ example.cpp -o example && ./example
