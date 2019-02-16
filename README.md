# big-data-project

## Introduction
This project deploys MNIST application into the container. Users submit digital pictures with handwritten characters through curl-XPOST command. This program first recognizes the pictures, and then returns the recognized numbers to users. Every time a user submits an image, identifies a text and timestamp information in MNIST, it is recorded in Cassandra for storage.

## Demo
usingWeb.mp4 and usingCurl.mp4 is demos of this project.
[![Demo](http://img.youtube.com/vi/T-D1KVIuvjA/0.jpg)](http://v.youku.com/v_show/id_XNDA2MjA1OTk1Mg==.html?spm=a2h3j.8428770.3416059.1)

## Files

app.py: main program

model.py: mnist model architecture

dockerfile

requirements.txt

img: some pictures of numbers used to test the app

model: perserved mnist model after training

big-data project.pdf: report of this project

using web.mp4: demo video using web to submit images

using curl.mp4: demo video using curl to submit images
