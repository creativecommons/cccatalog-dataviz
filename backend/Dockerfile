# pull official base image
FROM python:3.7.8-alpine

# set work directory
WORKDIR /backend

# install dependencies
RUN pip install --upgrade pip
COPY ./requirements.txt .
RUN pip install -r ./requirements.txt

# copy project
COPY ./src ./src