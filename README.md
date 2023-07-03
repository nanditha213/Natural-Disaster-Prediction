# Natural-Disaster-Prediction

This repo focuses on developing AI algorithms and models that utilize environmental data to predict and identify potential natural disasters, such as floods, wildfires, and earthquakes. The system will be able to provide early warnings and assist in disaster preparedness and response efforts. The Machine Learning model is deployed on Flask
which helps in implementing a machine learning application in Python that can be easily plugged, extended and deployed as a web application. 

For the Earthquake prediction, past seismic events data is used to predict future earthquakes in the Hindu Kush Mountain region. The dataset contains 22 columns and 14698 rows.
To prepare the data effectively, it is crucial to select the relevant columns. In this dataset, the following columns were chosen: mag, place, depth, nst, gap, and rms. These specific columns were selected because they provide significant contributions to the analysis and are essential for the task at hand. Other columns were excluded for different reasons, such as redundancy in the information they conveyed, a high percentage of null values (over 50%), lack of relevance to the models being used, or containing id information used solely for data numbering purposes. Some of the chosen columns have null values which need to be substituted with other values. For substituting, the mean, median and mode can be used. But to choose which method to use it is necessary to first look at the columns and then derive the best method to choose from them. 

Flood Detection has been done from images using Deep Learning techniques. I employed KERAS' pretrained MobileNet CNN and fine-tuned it for the particular flood detection (image classification) task.

For Forest Fire Dtection, Logistic Regression has been where the data set contains parameters like Area, Oxygen, Temperature, Humidity and Fire occurrence ( which takes the value of 0 or 1 ). A website has been implemented using Flask that predicts the probability of a forest fire taking place based on oxygen,temperature and humidity content.

To set up this project :
1) First clone the repository
  
2) Open the project on VS Code
  
3) Install Flask in the virtual environment by running the following command in the VS Code Terminal : python -m pip install flask
  
4) Now run the app.py file :
In the Integrated Terminal, run the app by entering the command python -m flask run, which runs the Flask development server. The development server looks for app.py by default. When you run Flask, you should see output similar to the following:
<img width="431" alt="image" src="https://github.com/nanditha213/Natural-Disaster-Prediction/assets/121084004/5cafda9b-e397-4952-b7a6-62ef48e60dc9">
If you see an error that the Flask module cannot be found, make sure you've run python -m pip install flask in your virtual environment. 

5) To open your default browser to the rendered page, Ctrl+click the http://127.0.0.1:5000/ URL in the terminal.


