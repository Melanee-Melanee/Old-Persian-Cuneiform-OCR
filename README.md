## The aim of this repository is creating an OCR model (convert image to text) for Old Persian Cuneiform 

This repository is inspired from [eBL project](https://github.com/ElectronicBabylonianLiterature) and is a part of [
Electronic Old Persian Library](https://github.com/Electronic-Old-Persian-Library) organization.

eBL has developed models for Babylonian cuneiform but I am going to develop my models for Old Persian cuneiform. 


## 3 OCR models are developed in this repository:
- ``` yolo_cnn_old_persian ```
- ``` tessearct_old_persian ```
- ``` easyocr_old_persian ```
## Current status of these 3 OCR models:
- ``` yolo_cnn_old_persian ``` : is not completed yet.
-  ``` tessearct_old_persian ``` is completed.
-  ``` easyocr_old_persian ``` is completed but needs more optimization.

## easyocr_old_persian

This model is developed based on [EasyOCR](https://github.com/JaidedAI/EasyOCR/blob/master/custom_model.md) repository for a custum model. 
If you see any error please check [issues](https://github.com/JaidedAI/EasyOCR/issues)

Trainer notebook:

https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/blob/master/easyocr_old_persian/trainer_easyocr_old_persian.ipynb

Using saved model:

https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/blob/master/easyocr_old_persian/model_easyocr.ipynb






## tessearct_old_persian:

https://github.com/Melanee-Melanee/Old-Persian-Cuneiform-OCR/blob/main/Tesseract_Old_Persian_OCR.ipynb

Please replace "myLang.traineddata" file in this directory: `/usr/share/tesseract-ocr/4.00/tessdata`

This tesseract pre-trained OCR model deciphers Old Persian cuneiform to English transcription and is developed by [S. Muhammad Hossein Mousavi](https://github.com/SeyedMuhammadHosseinMousavi/Extracting-Old-Persian-Cuneiform/tree/main
). [Tesseract](https://github.com/tesseract-ocr/tesseract) is one of the most powerful OCR models in the world.


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

To create pull requests for this repository please choose just these branches: issue, refactor and feature.


