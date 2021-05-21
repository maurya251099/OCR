# OCR Electoral data
The election commission of India had made the electoral data in the form of tabulated Image as a PDF which is kind of hard to extract. This repository consist of the OCR program to extract the data 

The image data as a pdf can however be extracted very easily with the consideration of techniques of OCR(Optical Character Recognition)
This involves, extensive preprosessing of data, finding the boundaries and extraction using LSTM neural Engine or cloud vision API

The steps involved are 
1. Image preprocessing
  1.1 Segmentation 
  1.2 increasing contrast and shrapness 
  1.3 Setting up threshold(otsu's method(preferably))

2. Text recognition 
 2.1 Vision API 
 2.2 Pytesseract or Keras-OCR

3. Text storage 
  3.1 Pandas dataframe to csv 
    3.1.1 Converting the dataframe to numpy array 
    3.1.2 Converting numpy array to csv(as the data is irregular)
 
