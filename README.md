# SEP: Computer Vision & Deep Learning

## Overview
This project is the result of the "Software Development Practical" held at the Ludwig Maximilian University of Munich (LMU) during the Winter Semester 2025/26.

Under the topic *Computer Vision & Deep Learning*, students of LMU were tasked with developing, training, and evaluating a Convolutional Neural Network (CNN) from scratch for the well-known Facial Emotion Recognition (FER) problem.

The practical course was supervised by Johannes Schusterbauer and Ming Gui, PhD students at LMU.

## Team Members
- Alen Alija
- Kilian Killer
- Leon Maibauer
- Richard Tscharke

## Preparation

Start by 

## Review Setup

If you do **not** want to train the model from scratch but instead use our pretrained model for evaluation, run `main.py`. The script will guide you through:

- CSV file generation for your own dataset
- Grad-CAM–based explainable AI for image and/or video input
- An interactive live demo using your webcam

## Training Setup

If you want to train your own model with custom dataset distributions and training configurations, start by downloading the following datasets:

### RAF-DB

1. Visit the official RAF-DB website or click here(http://www.whdeng.cn/RAF/model1.html#dataset)
2. Go to the "How to get the Password" section and follow the instructions
3. Within your received mail, open one of the Basic emotion links
4. Download and unzip the "Image" and "EmoLabel" folders
5. Place them both into a new folder and name it "RAF"

### Expression in the Wild

1. Visit the official ExpW website or click here(https://mmlab.ie.cuhk.edu.hk/projects/socialrelation/index.html)
2. Go to the "Downloads" section and open the ExpW link
3. Download the "data" folder
4. Unzip its contents by ...
5. Rename the data folder to "ExpW"

## KDEF

1. Visit the official KDEF website or click here(https://kdef.se/)
2. Go to "Download" -> "Download the original KDEF and AKDEF" and follow the instructions
3. Within your received mail, open
4. Download and...
5. Rename...

Finally, place all three folders (RAF, ExpW, KDEF) into the "data" folder within our project root.


Our project includes:
- Data Preparation & Preprocessing sripts for the RAF-DB, ExpW and KDEF datasets
- Three versions of CNN architectures showcasing our progress over the time
- Training & Evaluation scripts based on parameters configurable by any user
- Live demo with integrated FER and optional Grad-CAM explanation & Facial Keypoints detection
- Image & Video explaining scripts using Grad-CAM and optimization tools

This project was supervised by Johannes Schusterbauer & Ming Gui, PhD students at the LMU.
