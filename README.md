# Shotor
## Word Level OCR Dataset for Persian Language
Shotor (means camel in Persian) is a free synthetic dataset for Word Level OCR.

![Sample Images](https://raw.githubusercontent.com/amirabbasasadi/Shotor/master/demo.png)  

The current version contains 120000 grayscale images and corresponding words. The words contain only alphabet.  
**Note: To train a robust model, apply augmentations like scaling, translation, additive noise and ...  on the images.**  
To see an example of using the Shotor dataset see this notebook:  
[A simple word level OCR for Persian Language using Pytorch and OpenCV](https://github.com/amirabbasasadi/PersianOCR)  


I used these resourses to create word lists:  
- Persian Wikipedia
- [Ganjoor Website](https://ganjoor.net/)
- [Persian Spell Checking Data](https://github.com/reza1615/Persian-Spell-checker) by [reza1615](https://github.com/reza1615)

The images have been generated using multiple fonts:
- a few fonts from https://rastikerdar.github.io/
- and some fonts from https://www.fontirani.ir/  

Created by: Amirabbas Asadi (amir137825@gmail.com)
