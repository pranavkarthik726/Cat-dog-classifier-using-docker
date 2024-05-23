# Cats and Dogs docker Classification

This project demonstrates a simple web application that predicts whether an uploaded image contains a cat or not. It uses a pretrained machine learning model (h5 format). It is deployed using Flask and containerized using docker.

# Docker Deployement
Build the Docker image: docker image build -t flask_docker .

Run the Docker container: docker run -p 5000:5000 -d flask_docker

Access the app at http://127.0.0.1:5000/upload

# Usage
Upload an image using the web form.

The app will predict whether the image contains a cat or not.

# Demo Video
https://github.com/pranavkarthik726/Cat-dog-classifier-using-docker/assets/167102866/fd17b9b2-c475-458c-bd7c-871394c0ac37


Model link : https://huggingface.co/spaces/Sa-m/Dogs-vs-Cats/blob/main/best_model.h5

Docker hub: https://hub.docker.com/r/pranavkarthik726/flask_docker

