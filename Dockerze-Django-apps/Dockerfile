FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /bug
WORKDIR /bug
ADD . /bug
COPY ./requirements.txt /bug/requirements.txt
RUN pip install -r requirements.txt
COPY . /bug/
EXPOSE 8004


