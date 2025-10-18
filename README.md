# Deploy Model with Docker

A minimal, opinionated template to build and run a machine learning model inside Docker.

## Features
- Dockerfile for a Python model server
- Example run commands

## Prerequisites
- Docker 
- Python model file

## Quickstart (CPU)
1. Build the image:
    docker build -t ml-model .

2. Run the container:
    docker run ml-model

## Directory layout (suggested)
- Dockerfile
- requirements.txt
- model.py         

## Contributing
1. Create a branch
2. Make changes
3. Open a pull request