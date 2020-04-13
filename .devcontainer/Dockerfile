FROM ubuntu:latest

RUN apt-get update && \
    apt-get install git wget flex bison gperf python3 python3-pip python3-setuptools cmake ninja-build ccache libffi-dev libssl-dev -y && \
    # Make Python3 the default interpreter
    update-alternatives --install /usr/bin/python python /usr/bin/python3 10