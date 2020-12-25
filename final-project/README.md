<h1 align="center"> Football player spotting </h1>

This folder contains files of the final project for the Skoltech course "Introduction to Computer Vision".

## Dependencies
- Python
- NumPy
- OpenCV
- skimage

## Content

* **images** - folder with Pro Evolution Soccer 2016 screenshots which were used for checking of algorithm's work.
* **presentation** - folder with PDF presentation of results achieved
* **ipynb file** - implementation of the project in Jupyter notebook

## Video links
One of the project's result are shown in the video format.

Here are the links to:

Game recording: https://youtu.be/7tNIcEiqZhM

Tracking recording: https://youtu.be/YQVNW2ro4jE

## Accuracy for each image

It was calculated that for images in **images** folder the average accuracy is about 84%.

| N | Real amount (blue) | Real amount (red) | TP(red) | FP(red) | FN(red) | TP(blue) | FP(blue) | FN(blue) | Accuracy |
|:-:|:------------------:|:-----------------:|:-------:|:-------:|:-------:|:--------:|:--------:|:--------:|:--------:|
| 1 |         10         |         9         |    7    |    1    |    2    |    10    |     0    |     0    |   0,85   |
| 2 |          7         |         9         |    9    |    1    |    0    |     7    |     0    |     1    | 0,888889 |
| 3 |          9         |         7         |    6    |    1    |    0    |     8    |     1    |     1    | 0,823529 |
| 4 |          9         |         9         |    7    |    1    |    2    |     9    |     0    |     0    | 0,842105 |
| 5 |         10         |         9         |    8    |    1    |    1    |    10    |     1    |     0    | 0,857143 |
| 6 |         10         |         9         |    7    |    1    |    2    |     9    |     0    |     1    |    0,8   |
| 7 |         10         |         10        |    6    |    1    |    4    |    10    |     0    |     1    | 0,727273 |
| 8 |         10         |         10        |    10   |    1    |    0    |    10    |     0    |     1    | 0,909091 |
