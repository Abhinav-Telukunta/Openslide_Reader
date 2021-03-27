# Openslide_Reader

## Aim of project: This project develops a C reader which efficiently reads whole slide images and converts them to tfrecord file format of Tensorflow.


![workflow](https://github.com/Abhinav-Telukunta/Openslide_Reader/blob/main/workflow.PNG)

## Setup

* Install libvips as specified in libvips.docx file
* Take whole slide images from GDC portal as mentioned in WSI.docx file or any other website
* Run the Final_OpenSlider.ipynb file and change the file paths and directories according to your environment

## Languages

* Used C to convert WSI to Tiles
* Used Python to convert tiles to tfrecords and viceversa
