Diabetes Prediction:
Table of Content
Demo
Overview
Motivation
Installation
Deployement on Heroku
Directory Tree
Bug / Feature Request
Demo
Link: https://kidney26.herokuapp.com



Overview
This is a simple Flask web app which predicts whether a patient is having diabetes or not.

Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models. Finally it is important to work on application (real world application) to actually make a difference.

Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

pip install -r requirements.txt
Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.



Our next step would be to follow the instruction given on Heroku Documentation to deploy a web app.

Directory Tree
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── diabetes_model.pkl
├── requirements.txt
Technologies Used


  

Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue here by including your search query and the expected result
