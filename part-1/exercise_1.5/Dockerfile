FROM ubuntu:16.04

WORKDIR /mydir
COPY frontend-example-docker .

EXPOSE 5000

RUN apt-get update && apt-get install -y curl npm
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs
RUN npm install
RUN nodejs -v && npm -v

CMD API_URL=http://localhost:8000 npm start
