# EAST-Pretrained

### Introduction

Implement a scene text detection with a pre-trained model called [EAST: An Efficient and Accurate Scene Text Detector](https://arxiv.org/abs/1704.03155v2) and OpenCV.

* To build a EAST model take a look at this [repo](https://github.com/argman/EAST).


### Requirement
1. Detection
    * numpy - (pip install numpy)
    * imutils - (pip install imutils)
    * opencv-python - (pip install opencv-python)
1. Recognition
    * pytesseract - (pip install pytesseract)
    * and need to install [Google Tesseract OCR](https://github.com/tesseract-ocr/tesseract/wiki) (additional info how to install the engine on Linux, Mac OSX and Windows). 


### Run

 * ```python3 detection.py -i path/to/images```
 * ```python3 recognition.py -i path/to/images```
 

### Result
![Detection Result](https://github.com/shin7/Text-Detection/blob/master/images/detection-result.png)
