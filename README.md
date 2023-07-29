# Nonogram Computer Vision
This project aims to take nonograms from the website www.nonograms.org/ and translate them into a computer list format which can be then used to solve and show the completed nonogram.

The nonograms used to run this should be gathered from [here](www.nonograms.org/) and saved in a locally accessible folder.
Testing has be performed to ensure it works with PNG image file type others may be supported.

## Requirements
- [CV2](https://pypi.org/project/opencv-python/)
- [Numpy](https://numpy.org/)
- [Pytesseract](https://pypi.org/project/pytesseract/)
- [Tesseract] (https://pythonforundergradengineers.com/how-to-install-pytesseract.html)
You can then use the command
**where tesseract**
and at the top of Finale.ipynb insert this file location which will allow pyTesseract to interact with Tesseract.



# Examples
<img src="example_with_bounding_boxes.jpg"
     alt="Image showing the nonogram isolation which allows us to harvest the digits."/>

<img src="TestNonograms/Example5.png"
     alt="Original Image"/>