FROM ubuntu:20.04
RUN apt update && apt install python3 -y && apt install python3-pip -y && pip3 install flask
RUN mkdir -p docker/python
COPY app.py /docker/python
EXPOSE 8080
CMD ["python3", "/docker/python/app.py"]
