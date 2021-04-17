# Optical Character Recognition

## Server 

```
34.205.65.225
```


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

## Languages 

```bash
sudo apt-get install tesseract-ocr-[lang]

# [lang] can be :
all
# or
afr
amh
ara
asm
aze
aze-cyrl
bel
ben
bod
bos
bul
cat
ceb
ces
chi-sim
chi-tra
chr
cym
dan
dan-frak
deu
deu-frak
dev
dzo
ell
eng
enm
epo
est
eus
fas
fin
fra
frk
frm
gle
gle-uncial
glg
grc
guj
hat
heb
hin
hrv
hun
iku
ind
isl
ita
ita-old
jav
jpn
kan
kat
kat-old
kaz
khm
kir
kor
kur
lao
lat
lav
lit
mal
mar
mkd
mlt
msa
mya
nep
nld
nor
ori
pan
pol
por
pus
ron
rus
san
sin
slk
slk-frak
slv
spa
spa-old
sqi
srp
srp-latn
swa
swe
syr
tam
tel
tgk
tgl
tha
tir
tur
uig
ukr
urd
uzb
uzb-cyrl
vie
yid
```


## Usage

        python ocr_simple.py image.jpg
