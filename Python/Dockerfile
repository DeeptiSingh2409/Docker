# Use an official Python runtime as a parent image
FROM python:3.7-slim

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

RUN pip install flask

EXPOSE 8080

# Run hello_world.py when the container launches
CMD ["python", "hello_world.py"]

#
