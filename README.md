# OCR Electoral data
The election commission of India had made the electoral data in the form of tabulated Image as a PDF which is kind of hard to extract. This repository consist of the OCR program to extract the data 

The image data as a pdf can however be extracted very easily with the consideration of techniques of OCR(Optical Character Recognition)
This involves, extensive preprosessing of data, finding the boundaries and extraction using LSTM neural Engine or cloud vision API

The steps involved are 
1. Image preprocessing
Segmentation 

increasing contrast and shrapness 
  
Setting up threshold(otsu's method(preferably))

2. Text recognition 

 Vision API 
 
 Pytesseract or Keras-OCR

3. Text storage 

   Pandas dataframe to csv 
  
   Converting the dataframe to numpy array 
    
   Converting numpy array to csv(as the data is irregular)
 
