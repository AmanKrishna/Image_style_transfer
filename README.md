# MTP2019-ImageStyleTransfer

This project is based on the paper "Image-to-Image Translation with Conditional Adversarial Networks" by Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros.

## Running instructions

First you need to download the [CMP Facade](http://cmp.felk.cvut.cz/~tylecr1/facade/) dataset.

Go into pix2pix directory.

Then, run python3 build_dataset.py 'path to CMP_facade_DB_base' to transform the data.

Finally, run python3 example.py and the output will be saved in pix2pix/images folder.

## Requirements

Python 3.5

Tensorflow

## The following is the result after training the model for 9500 epochs
![alt text](https://github.com/AmanKrishna/Image_style_transfer/blob/master/pix2pix/Output/iter_9500.jpg)

