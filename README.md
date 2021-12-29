# Image-Processing-CIPLA
Computer Vision Models for Surveillance Cameras inside CIPLA Labs

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

## Requirements
<li> Python 3 </li>
<li> Jupyter Notebook </li>
<li> 8-16 GB RAM </li>

## Get Started 🤞
<li> To install python libraries required for the models <br>
 
  ```
  pip install -r requirements.txt
  ```
  
</li><hr>

## Eye Detector
<li>Change the video feed to the path of the video or let it be 0 to use it on Web Camera</li>
<li>Change the threshold to adjust the eye-nose distance</li>
<li>Run the cell to start the eye detector</li>
<li>Press the 'q' button to Quit</li>
<hr>

## Lean Detector
<li>Change the video feed to the path of the video or let it be 0 to use it on Web Camera</li>
<li>Change the threshold_angle to adjust the leaning angle</li>
<li>Run all the cells from top to start the lean detector</li>
<li>Press the 'q' button to Quit</li>
<hr>

## Motion Detector
<li>Change the video feed to the path of the video or let it be 0 to use it on Web Camera</li>
<li>Run the cell start the lean detector</li>
<li>Press the 'q' button to Quit</li>
<hr>

## Multi-Person Pose Estimator
<li>Currently works only on images</li>
<li>Open the colab notebook and run the cells sequentially</li>
<li>To run the detector on our own images:

  ```
  run_detector(detector, <path-to-image>)
  ```
</li>
<hr>

## People Counter
<li>Currently works only on images</li>
<li>Change the image path</li>
<li>Run the cells sequentially to start the People Counter</li>
<li>Press the Esc button to Quit</li>
<hr>

## Static Wall Touch Detector
<li>Currently works only on images</li>
<li>Change the image path and the wall coordinates</li>
<li>Adjust the min threshold distance to consider touching 
<li>Run the cells sequentially to start the Wall Touch detector</li>
<li>Press the Escape button to Quit</li>
<hr>

## Sit Detector
<li>Change the video feed to the path of the video or let it be 0 to use it on Web Camera</li>
<li>Run the cells sequentially start the Sit detector</li>
<li>Press the 'q' button to Quit</li>
<hr>
