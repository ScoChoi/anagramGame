FROM python:3.7
MAINTAINER Scott Choi "ascottychoi@gmail.com"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
COPY . /flask_vocab.py
WORKDIR /flask_vocab.py
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]
