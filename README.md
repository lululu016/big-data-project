# big-data-project

This project deploys MNIST application into the container. Users submit digital pictures with handwritten characters through curl-XPOST command. This program first recognizes the pictures, and then returns the recognized numbers to users. Every time a user submits an image, identifies a text and timestamp information in MNIST, it is recorded in Cassandra for storage.


app.py: main program

predict.py: predict program (using mnist softmax model)

model.py: mnist model architecture

dockerfile

requirements.txt

img: some pictures of numbers used to test the app

model: perserved mnist model after training

big-data project.pdf: report of this project

lilu-project.mov: demo video
