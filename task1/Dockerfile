# Base image
FROM ubuntu:latest

# Update APT
RUN apt-get update -y

# Install Python 3, pip, and Flask
RUN apt-get install -y python3 python3-pip
RUN pip3 install flask

# Set the working directory
WORKDIR /app

# Copy the Python file
COPY api.py /app

# Expose the Flask app port
EXPOSE 5252
