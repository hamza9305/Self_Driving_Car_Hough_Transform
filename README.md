# Self_Driving_Car_Hough_Transform


The script [HoughTransform.py](https://github.com/hamza9305/Self_Driving_Car_Hough_Transform/blob/main/HoughTransform.py) makes use of Hough Transform to detect lanes in an image where lane markings are found using a canny edge detector. The rgb image is first converted to grayscale and then a gaussian blur is applied to the image. The kernel size and thresholds can be adopted and applied to the grayscale image to find lane markings. The parameters of Hough lines function can be adopted to detect straight elongated lines.

<p align="center">
  <img width="480" height="270" src="https://github.com/hamza9305/Self_Driving_Car_Hough_Transform/blob/main/resource/test.jpg">
</p>
<p align="center">
  <img width="480" height="270" src="https://github.com/hamza9305/Self_Driving_Car_Hough_Transform/blob/main/resource/blur_gray.jpg">
</p>
<p align="center">
  <img width="480" height="270" src="https://github.com/hamza9305/Self_Driving_Car_Hough_Transform/blob/main/resource/masked_edges.jpg">
</p>
<p align="center">
  <img width="480" height="270" src="https://github.com/hamza9305/Self_Driving_Car_Hough_Transform/blob/main/resource/combined.jpg">
</p>

