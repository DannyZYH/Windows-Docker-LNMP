FROM nginx:latest
RUN mv /etc/apt/sources.list /etc/apt/sources.list.bak
COPY sources.list /etc/apt/
RUN apt-get update
RUN apt-get install -y vim