# The aim of this repository is creating an OCR model (convert image to text) for Old Persian Cuneiform 

This repository is inspired from [eBL project](https://github.com/ElectronicBabylonianLiterature) and is a part of [
Electronic Old Persian Library](https://github.com/Electronic-Persian-Old-Library) organization.

eBL has developed models for Babylonian cuneiform but I am going to develop my models for Old Persian cuneiform. 


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

## Google drive link

The project directories are accessible on this google drive link:

https://drive.google.com/drive/folders/1ZirD_a_6QMnrCwdlmt2i78TLjcUZid66?usp=sharing


## Annotation

Use annotation online tools like [CVAT](https://www.cvat.ai/) or [labelImg gitHub](https://github.com/HumanSignal/labelImg).

## Main notebook

Please open this notebook and work on Google Colab: 

https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/blob/main/Old_Persian_Cuneiform_OCR.ipynb




## pre-trained OCR model by tesseract:

https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/blob/main/Tesseract_Old_Persian_OCR.ipynb

This pre-trained OCR model converts Old Persian cuneiform to English transcription and is taken from [Dr Mousavi](https://github.com/SeyedMuhammadHosseinMousavi/Extracting-Old-Persian-Cuneiform/tree/main
).


An example:

Input:

![d1](https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/assets/74653444/c5254f90-0fe7-4802-908c-c4cd184a4043)



Output:

Zatiy ; dalyvu S ; xSay

Zdy mna;aul bpmma;u stam;

blT uv; Nnda ; VdZdbiS ; bgd

bdS;uta;dmam;dhyaum;aul

mzda ; paTuv ; Qca;hd bay

a;Qca ; QuSdyala ; Nnca; dl

uga ;abdy ;dmam ;dhyaum ;ma

;ajM iya

## At the next step, you can translate this output by Chat-GPT:


![old persian translation by chatgpt](https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/assets/74653444/a6bb5252-ec6d-4dda-8ce8-7d792e656e7c)



## Notice

This repository is still under developing. For contributing contact me by email: melaneepython@gmail.com 

To create pull requests for this repository please choose branches except "main" (issue, refactor and feature).


