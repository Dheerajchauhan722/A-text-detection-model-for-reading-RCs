# A-text-detection-model-for-reading-RC

In this project we use Python-tesseract. Python-tesseract is an optical character recognition (OCR) tool for python. That is, it will recognize and “read” the text embedded in images.


We also used image enhencement technique for better text fetching such as brightness,color.

Before starting we need to install pytesseract in anaconda command prompt (pip install pytesseract). Also we need to install tesseract.exe and assign its directory link is here(https://github.com/tesseract-ocr/tesseract/wiki/4.0-with-LSTM#400-alpha-for-windows).So after applying tesseract we will have string of text available on image.


after that we will split text on the basis on space. so we will having a list of words.
After that we make searching operations for 
"Regn number",
"Chassis number",
"Name",
"Engine number",
"Registration date",
"Mfg. date".
after that make dataframe of this fetched data and save it in form of excel file. 


In mostly images registration date is not given so i had used None at that place.Also if any data is not given or unable to fetched from the image i have Printed None
