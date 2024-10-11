
## Melanee: This repository is still under developing.



## Steps:

1. Dataset Preparation: Annotate images with bounding boxes around each character.

2. Environment Setup: Install necessary libraries and import them.

3. Text detection: Train a YOLO model to detect characters in the dataset.

4. Text recognition: Train a CNN model to recognise characters.

5. Inference: Use YOLO for character detection and the CNN model for recognition on the custom image. 

6. Visualization: Display detected and recognized text on the custom image.


![Screenshot from 2024-07-08 17-13-24](https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/assets/74653444/5f82f3d7-5f2c-4094-8c10-bdb755f4fddd)


## Primary data

Primary data is taken from: https://www.kaggle.com/datasets/hosseinmousavi/achaemenid-inscription-ocr

Please notice that I am at the beginning of this project and I will prepare a more high qulity dataset (real images) in the future. 


## Pre-processing

I did not use any pre-processing for the image dataset yet! I will do in the future. 

## Google drive link

The project directories are accessible on this google drive link:

https://drive.google.com/drive/folders/1ZirD_a_6QMnrCwdlmt2i78TLjcUZid66?usp=sharing


## Annotation

Use annotation online tools like [CVAT](https://www.cvat.ai/) or [labelImg gitHub](https://github.com/HumanSignal/labelImg).

## Main notebook

Please open this notebook and work on Google Colab: 

https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/blob/master/yolo_cnn_old_persian/yolo_cnn_old_persian.ipynb
