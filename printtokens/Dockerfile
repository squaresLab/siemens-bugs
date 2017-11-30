FROM ubuntu:16.04

RUN mkdir -p /experiment
WORKDIR /experiment
ADD printtokens_2.0.tar.gz .

# remove unnecessary information
RUN cd printtokens && \
    rm -rf  traces \
            info \
            newoutputs \
            version \
            testplans \
            source \
            source.alt \
            outputs \
            versions

ARG scenario
