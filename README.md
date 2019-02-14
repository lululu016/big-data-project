# big-data-project

## Introduction
This project deploys MNIST application into the container. Users submit digital pictures with handwritten characters through curl-XPOST command. This program first recognizes the pictures, and then returns the recognized numbers to users. Every time a user submits an image, identifies a text and timestamp information in MNIST, it is recorded in Cassandra for storage.

## Demo

<video src="/Users/apple/Documents/GitHub/big-data-project/usingCurl.mp4"></video>

<video src="/Users/apple/Documents/GitHub/big-data-project/usingWeb.mp4"></video>



<iframe 
    width="800" 
    height="450" 
    src="https://github.com/lululu016/big-data-project/blob/master/usingCurl.mp4"
    frameborder="0" 
    allowfullscreen>
</iframe>


## Files

app.py: main program

model.py: mnist model architecture

dockerfile

requirements.txt

img: some pictures of numbers used to test the app

model: perserved mnist model after training

big-data project.pdf: report of this project

using web.mov: demo video using web to submit images

using curl.mov: demo video using curl to submit images
