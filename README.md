# Openslide_Reader

## Aim of project: This project develops a reader which efficiently reads whole slide images and converts them to tfrecord file format of Tensorflow.


![workflow](https://github.com/Abhinav-Telukunta/Openslide_Reader/blob/main/workflow.PNG)

## Setup

Step-1: I have taken the following 5 whole slide images from [TCGA](https://portal.gdc.cancer.gov/repository?filters=%7B%22op%22%3A%22and%22%2C%22content%22%3A%5B%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.data_format%22%2C%22value%22%3A%5B%22svs%22%5D%7D%7D%5D%7D) :

  *	TCGA-BS-A0T9-01A-01-TSA.f1c68c45-c2e2-447a-9798-a60e4ff5da69.svs
  *	TCGA-DX-A3LS-01A-01-TSA.1CA7E5BE-439B-4552-B4BC-40E9F396C1C3.svs
  *	TCGA-P5-A5F4-01A-01-TSA.ECCBFA45-E2BC-4D8F-90D1-1ED7DBFE1F18.svs
  *	TCGA-VM-A8CD-01A-01-TS1.CB6F9C97-4181-4B00-8112-EDFDDA2C38AD.svs
  *	TCGA-BG-A0VX-01A-01-MS1.a9f524cf-2ac3-40fb-8d24-61224aea7dc6.svs

Step-2: Install openslide-python using following commands:
  
  ```
  apt update && apt install -y openslide-tools
  pip install openslide-python
  ```

Step-3: Run the Project.ipynb file and change the file paths and directories according to your environment


