# Image-Recognition-Service-
A Vue.js based web app that can capture pictures from the users’ webcam and uploads it to an AWS S3 Bucket which then triggers AWS Lambda (Serverless Function). Azure's Computer Vision API is called by AWS Lambda which returns metadata after image processing which is then stored to GCP’S Firestore NoSQL Database.
