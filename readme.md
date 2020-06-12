# Optical Character Recognition

## Prerequisite

### Install Tesseract 4.0 on Ubuntu 18.04

```
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
sudo pip install pytesseract
```

### OpenCV

If you need only main modules (standard desktop) : ```  pip install opencv-python  ```

If you need both main and contrib modules  (standard desktop) : ``` pip install opencv-contrib-python ```

**If you need only main modules (server) :** ```pip install opencv-python-headless ``` 

If you need both main and contrib modules (server) : ``` pip install opencv-contrib-python-headless```

## Source

* [Tutorial](https://www.learnopencv.com/deep-learning-based-text-recognition-ocr-using-tesseract-and-opencv/)
* [OpenCV](https://pypi.org/project/opencv-python/)
* [PyTesseract](https://pypi.org/project/pytesseract/)


## Usage

        python ocr_simple.py image.jpg
