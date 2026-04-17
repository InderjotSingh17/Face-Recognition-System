# Face Recognition System

This project detects faces and identifies whether they belong to the same person using deep learning.

## Features
- Face detection using MTCNN
- Face embeddings using FaceNet (InceptionResnetV1)
- Face comparison using cosine similarity
- Automatic labeling (Person 1, Person 2)

## Tech Stack
- Python
- OpenCV
- PyTorch
- facenet-pytorch

## How it works
Image → Face Detection → Embedding → Similarity → Label
