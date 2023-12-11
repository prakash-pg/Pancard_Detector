# Pancard_Detector


This Python script performs image tampering detection using Structural Similarity Index (SSIM) and contour analysis. It fetches two images from URLs, prints their format and size, resizes and saves them, displays the resized images, converts them to grayscale, computes the SSIM, displays the difference image, calculates the threshold, finds contours, draws bounding rectangles around contours on original and duplicate images, and displays the images with contours along with the difference and threshold images. The script combines PIL and OpenCV for these tasks.

# Running the Flask_App_Website

cd "X:\projects\pancard-fake detection\Pan_Card_flask_app"
>> conda activate my_flask_env
>> 
>> pip install -r requirements.txt
>> 
>> python app.py

Change directory to the specified path, activate the 'my_flask_env' Conda environment, install required packages from the 'requirements.txt' file, and run the Flask web application using 'app.py'.
