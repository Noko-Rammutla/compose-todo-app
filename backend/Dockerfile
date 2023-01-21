FROM python:3.12-rc-alpine

# set the working directory
WORKDIR /app

# install dependencies
COPY ./requirements.txt /app/requirements.txt
RUN pip install --no-cache-dir --upgrade -r /app/requirements.txt

# copy the src to the folder
COPY . ./app
