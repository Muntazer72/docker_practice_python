# Flask Docker Addition App

A simple Flask web application that adds two numbers.
The app is containerized using Docker.

## Features
- Flask backend
- HTML + CSS UI
- Docker container support

## Run with Docker

Build image

docker build -t flask-addition-app .

Run container

docker run -p 5000:5000 flask-addition-app

Open in browser

http://localhost:5000
