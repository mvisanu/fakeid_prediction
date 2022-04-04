Machine Learning -  ID Card Detection

1. Get images from user
2. Check for size and format the image
3. Change shape and size of image according to the original image
4. Convert the image to grayscale
5. Find the similarity index of images
6. find the threshold of the image
7. Find contour and grap those ocontour using Imutils
8. Draw a bounding rectangle using these contours.
9. Plot difference, threshold, original and tampered image
10. Compare all the images and check the similarity score to deside tampering




Steps to run Flask API application:

Step 1:	Create the copy of the project.

Step 2: Open command prompt and change your current path 
to folder where you can find 'app.py' file.

Step 3: Create environment by command given below-
conda create -name <environment name>
  
Step 4: Activate environment by command as follows-
conda activate <environment name>
  
Step 5: Use command below to install required dependencies-
python -m pip install -r requirements.txt
  
Step 6: Run application by command;
python app.py
You will get url copy it and paste in browser.
  
Step 7: You have sample_data folder where you can get images to test.
