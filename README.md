## The aim of this repository is creating an OCR model (convert image to text) for Old Persian Cuneiform 

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


## Pre-processing

I did not use any pre-processing for the image dataset yet! I will do in the future. 

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

This [tesseract](https://github.com/tesseract-ocr/tesseract) pre-trained OCR model converts Old Persian cuneiform to English transcription and is developed by [S. Muhammad Hossein Mousavi](https://github.com/SeyedMuhammadHosseinMousavi/Extracting-Old-Persian-Cuneiform/tree/main
).


An example: 

The last 12 lines of the great Darius's inscription in Persepolis, [DPd inscription](https://www.livius.org/sources/content/achaemenid-royal-inscriptions/dpd/):

Input:

![darius2](https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/assets/74653444/fc8f2a4c-b8b4-4b46-97e3-c87d506fd6fd)



Output:

Zatiy ; daryvuS ; xSayZiy;

mna;aurmzda;upstam; blauv;

hda ; ViZibiS ; bgibiS ; uta;

imam;dhyaum;aulmzda;

paTuv;hca;hinaya; hca;

QuSiyala ; hca;druga;abiy;

imam ;dhyaum;ma; ajMiya; ait;

aim ;yanm;jDiyaMiy;

aitmiy ; ddaTuv

## At the next step, you can translate that Old Persian transcription to modern Persian by [Chat-GPT](https://chatgpt.com/):



این منم داریوش شاهنشاه؛
به لطف اهورامزدا، من این را بنا کردم؛
من این امپراتوری را بنیان نهادم و آن را نیرومند ساختم.
باشد که اهورامزدا من و پادشاهی مرا محافظت کند؛
باشد که برای همیشه پایدار بماند؛
و باشد که از دروغ در امان باشد؛
این است آنچه من انجام دادم؛

این است آنچه من می‌گویم.



## Notice

This repository is still under developing. For contributing contact me by email: melaneepython@gmail.com 

To create pull requests for this repository please choose branches except "main" (issue, refactor and feature).


