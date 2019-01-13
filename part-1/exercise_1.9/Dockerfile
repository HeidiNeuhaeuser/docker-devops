FROM ubuntu:16.04

WORKDIR /mydir

RUN apt-get update && apt-get install -y python3
RUN apt-get update && apt-get install -y python3-pip
RUN pip3 install --upgrade pip
RUN pip3 install numpy

ENV PATH /:$PATH

CMD ["python3"]
