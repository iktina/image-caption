# Image Caption

## Welcome

The service receives an image and uses it as an input for a pre-trained model.

## What’s the point?

The service generates a text description for the image using machine learning techniques. The service receives the image in binary format and outputs a text string that is a text description of the scene in the image.

##  How does it work?

The user must provide `the path to the image` to which the scene description needs to be created.

inputs:

* `mothod`: ofa_caption
* `input_data`: image

## Expected result

### Input
<img src="https://i7.imageban.ru/out/2022/08/30/7b3d3bb33a75797483e48005d49e784a.jpg" width="200" />

### Answer
```
a woman in a yellow dress holds a bouquet of wildflowers in a wheat field
```
