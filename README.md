# yolov8_numberplate
implementation of Yolo v8
Installed packages

•	Python 3.10.12

•	pytesseract Version: 0.3.10

•	opencv-python Version: 4.8.0.76

•	yolo v8

LicensePlateDetector Class

•	Created a method named detect_license_plate. Which accepts the image as input.
•	Inside this method, code for error handling if the user input a value other than a str object or a NumPy array.
•	Predicted an image using a custom-made yolov8 model for detecting number plates.
•	Extracted the bounding box coordinates, and drew the bounding box using the OpenCV module.
•	Applied OCR technique on the selected area for extracting the characters inside the bounding box using pytesseract and wrote the text above the bounding box.


Custom made model

Collected images of vehicles with number plate
Annoted the images using labelImg
Trained the labeled data using Yolo v8 with 200 epochs.
Extracted the saved model and made the prediction. 
