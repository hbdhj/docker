# Python base image
FROM python:3.6.3

# Where the API server lives
WORKDIR /app/  

# Install required dependencies  
COPY requirements.txt /app/  
RUN pip3 install -r ./requirements.txt