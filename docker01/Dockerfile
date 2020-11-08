FROM ubuntu:16.04

MAINTAINER Changjun Park <pcj006@gmail.com>

RUN apt-get update
RUN apt-get install -y python python-pip

ADD hello.py /home/hello.py
ADD app.py /home/app.py
add requirements.txt /home/requirements.txt

expose 5000

workdir /home
run pip install -r requirements.txt


CMD ["/home/app.py"]
ENTRYPOINT ["python"]
