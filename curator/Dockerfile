# set base image (host OS)
FROM python:3.8

# set the working directory in the container
WORKDIR /code

RUN git clone https://github.com/Ruukas97/Curator.git

WORKDIR /code/Curator

# install dependencies
RUN pip install -r requirements.txt

# command to run on container start
CMD [ "python", "-u", "bot.py" ]