# Gender-predictor
Gender predictor app deployed using Flask

This app is driven by data and machine learning model. As soon as you upload image,in the background it convert it into grayscale, crop face, convert into eigen image and finally it model to predict. All this functionality dumped in the flask app. 

# Prerequisites

you must have Scikit Learn, CV2, Numpy, Pandas, HTML, CSS nd Flask installed.

# Project Structure

This project has six major parts :

 1. Model : It contains pickle files which need to loaded
 2. app : It contains Pipeline model and code to render Html templates
 3. static : It contains css style, images for web pages, upload & predict image files.
 4. templates - This folder contains the HTML template
 5. main.py : It contains code to build flask application on the local development server.
 
# Running the project

1. Make sure you are in the project home directory, and run below command.

  python main.py
  
2. By default, flask will run on port 5000. Navigate to URL http://127.0.0.1:5000/

3. Click on FaceApp, try it by uploading image and predict. Demo is uploaded for your reference.

Please give a ⭐ if you like. Thank you !!!
