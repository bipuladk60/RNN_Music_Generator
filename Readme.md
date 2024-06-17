# Music Generation with Recurrent Neural Networls(RNNs)
This project uses Recurrent Neural Networks (RNN) with LSTM layers to generate music in ABC notation.

## Introduction
This project aims to create a deep learning model capable of generating music. By training on a dataset of songs in ABC notation, the model learns musical patterns and can generate new compositions. The project leverages TensorFlow and Keras for model building and training, and integrates Comet.ml for experiment tracking.

## Installation
Clone the repository
```
git clone https://github.com/bipuladk60/RNN_Music_Generator.git
```
Make sure to install the following dependencies in your environment
```
!pip install comet_ml > /dev/null 2>&1
```
```
!pip install mitdeeplearning --quiet
```
```
!apt-get install abcmidi timidity > /dev/null 2>&1
```

## Results
Here is a sample result from the model:
```X:1
T:Example
M:4/4
K:C
L:1/8
K:A Dorian
FG|ABce fcAF|GEEF GFEC|DB,ED EDB,|EFE EFD|FGF E2D D2C|A,CE cEE|DED AGF|GEE E2:|!
```
This ABC notation when converted to MIDI sounds like this: 
[![Watch the video](https://www.dropbox.com/scl/fi/1el468n44sta8gkz4dyvk/output_0.mov?rlkey=s3i87v0bja94euasul9vsdz2k&st=y2yb9wpg&dl=0)