# Computer-Vision-Introduction
## Programs consist of computer vision topics.
### 1. QR Code Detector and Decoder
OpenCV Functions to Use 

a. Reading and writing image: cv2.imread(), cv2.imwrite()
<br>
b. Write text on image: cv2.putText()
<br>
c. Draw a line on image: cv2.line()
<br>
d. QR Detection: cv2.QRCodeDetector(), detectAndDecode()
<br><br>
<img src= "QR Code Detector/IDCard-Satya.png">
<br><br>
### 2. Using the Mouse for Annotation
In this program, I have create a GUI application which will let the user create a bounding box around a face present in the input image and save the cropped face automatically.
<br><br>
<img src= "Using the Mouse for Annotation/window.png" width="300" height="300">
<br><br>
### 3. Resize Image using Trackbar
In this program, I've to create a GUI application which will be an extension of the trackbar. In this program, only scaling up was implemented. My GUI application should be able to allow user to scale up as well as scale down an image. 
<br><br>
<img src= "Resize Image using Trackbar/resize_image.png" width="300" height="300">
<br><br>
### 4. Implementation of Morphological Operations
In this program, I've implement both the dilation and erosion from scratch and display the final (correct) image of both the operations. Create two video of intermediate steps of dilation and erosion using VideoWriter. 
<br><br>
<img src= "Implementation of Morphological Operations/dilate_erode.png" width="600" height="300">
<br><br>
### 5. Coin Detection
In this Coin Detection program, I've apply various mophological operations and different thresholding techniques in this practical application.
<br><br>
<img src= "Coin Detection/data/images/CoinsA.png" width="300" height="300">
<img src= "Coin Detection/data/images/CoinsB.png" width="500" height="300">
<br><br>
### 6. Color Spaces
In this program, I've implement OpenCV's cvtColor function from scratch for the following conversions:

1. convertBGRtoGray function for converting BGR image to Grayscale image. (BGR = Blue-Green-Red)

2. convertBGRtoHSV function for converting BGR image to HSV image. (HSV = Hue-Saturation-Value)
<br><br>
<img src= "Color Spaces/window.png" width="700" height="300">
<br><br>
