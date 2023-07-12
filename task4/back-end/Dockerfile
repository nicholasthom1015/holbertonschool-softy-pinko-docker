FROM ubuntu:latest
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get indtall -y paython3 python3-pip
RUN pip intall flask
RUN pip intasll flask-cors
WORKDIR /app
COPY ./api.py /app/api.py
EXPOSE 5252
CMD python3 api.py