# Lesion_detection

This repository implements an Automated Lesion Detection system deployable in a server. [Fully Convolutional Densenet](https://arxiv.org/pdf/1611.09326.pdf) is used to identify Lesions from Colonoscopy images. [Flask](https://www.fullstackpython.com/flask.html), a micro web framework written in python, is used to create a simple web application (using HTML)  in which users can upload Whole Slide Images (WSI) and the system will produce a report after carrying out inference on the uploaded image.

## Installation 

To clone this repository run (from the parent directory)
```bash
git clone https://github.com/Harikr16/Lesion_detection.git
```

## Requirements

Cuda 10.1

Pyhton 3.6

Required packages can be installed by running 
```bash
pip install -r requirements.txt
```

## Project Status

Report Generation Pipeline is under development.

GUI for Expert pathologist verification is under development.


## Support 

In case of any help needed, please feel free to reach out at -  sreeharitirur@gmail.com / harikrishnankr16@gmail.com

## Authors and Acknowledgements

This repository was developed for **Philips Code to Care** Challenge. 

Authors : [Harikrishnan R](https://github.com/Harikr16)  &  Sreehari S


