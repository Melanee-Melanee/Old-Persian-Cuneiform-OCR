# The aim of this repository is creating an OCR model (convert image to text) for Old Persian Cuneiform to match broken tablets or inscriptions

This repository is inspired from [eBL project](https://github.com/ElectronicBabylonianLiterature) and is a part of [
Electronic Old Persian Library](https://github.com/Electronic-Persian-Old-Library) organization.

eBL has developed models for Babylonian cuneiform but I am going to develop my models for Old Persian cuneiform. 


## Melanee: This repository is still under developing and I have not developed an OCR model yet!


# Stage 1 : Developing OCR model

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

## Google drive link

The project directories are accessible on this google drive link:

https://drive.google.com/drive/folders/1ZirD_a_6QMnrCwdlmt2i78TLjcUZid66?usp=sharing


## Annotation

Use annotation online tools like [CVAT](https://www.cvat.ai/) or [labelImg gitHub](https://github.com/HumanSignal/labelImg).

## Main notebook

Please open this notebook and work on Google Colab: 

https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/blob/main/Old_Persian_Cuneiform_OCR.ipynb



# Stage 2: Matching broken tablets or inscriptions by NLP

![old-persian](https://github.com/Melanee-Melanee/Persian-Old-Cuneiform-OCR/assets/74653444/986c2b5e-6d5e-4828-89be-4ba7d9050bc4)

(Photo is from Apadana Castle Shush, [Ref](https://www.livius.org/pictures/iran/susa/susa-apadana/susa-dsf-old-persian/))


This project leverages Optical Character Recognition (OCR) and Natural Language Processing (NLP) technologies to read and match the texts. Specifically, I use OCR to convert the cuneiform signs from images into machine-readable text. Then I will use [Prof Enrique Jiménez’s](https://www.assyriologie.uni-muenchen.de/personen/professoren/jimenez/index.html) project to apply [algorithms](https://github.com/ElectronicBabylonianLiterature/ngram-matcher) to detect and match segments of different tablets or inscriptions, aiding in the reconstruction of fragmented texts.

For more the details, please check my new article on [Medium](https://levelup.gitconnected.com/the-electronic-babylonian-library-ebl-gilgamesh-project-f883e0ff068f) and [eBL documentation](https://github.com/ElectronicBabylonianLiterature/generic-documentation). 


This repository is still under developing. For contributing contact me by email: melaneepython@gmail.com 

Notice: To create pull requests for this repository please choose branches except "main" (issue, refactor and feature).







