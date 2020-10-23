# Using Flask and python

# 1 > Store data in MongoDB. Retrieve it using Python and Flask  - ASG01.py
# 2 > Create an endpoint in Python to pass on that data to the front-end i.e. create an API (Service) - ASG02_REST_API.py

# Step 1:- 
- Create an environment
- Create a project folder and a venv folder within:

$ mkdir myproject
$ cd myproject

- On Windows:

$ py -3 -m venv venv

# Step 2:-
- Activate the environment
- Before you work on your project, activate the corresponding environment:

$ . venv/bin/activate

- On Windows:

> venv\Scripts\activate

- Your shell prompt will change to show the name of the activated environment.

# step 3:- 

- Install Flask

- Within the activated environment, use the following command to install Flask:

$ pip install Flask

# step 4:- 

- To, install Flask-PyMongo use the following command :

$ pip install Flask-PyMongo

# step 5:- 
- Install pandas
- pandas can be installed via pip from PyPI, use the following command :

$ pip install pandas

# step 6:-
 - Extract  Zip file
 - Copy ASG01.py and ASG02_REST_API.py file into your directory where you created an environment
 - copy csv and json data file in the same directory where you put AS01.py file
 
 # step 7:-
 - Inorder to run your ASG01.py and ASG02_REST_API.py 
 - you nedd to set your flask app by executing following command in command line
  -> for ASG01.py
   >set FLASK_APP=ASG01.py
   >flask run
 -  In order to see the Output , type the following URI on web browser
 -    http://127.0.0.1:5000/
 - URI will direct you to on web page where you will see the option to Insert a data in mongodb and view the data
 - Inorder to insert a data into mongo db , you have option to upload file data such as .csv and .json file data
 # Note : .csv and .json file must be in the same directory where your ASG01.py file is their.
   
  -> for ASG02_REST_API.py
   > set FLASK_APP=ASG02_REST_API.py
   >flask run
  - In order to see the output of ASG02_REST_API , you can make use of POSTMAN or web browser running on your machine.
  - Only get request is accepted on this app
  - access and TEST the API, you can type on POSTMAN or Web Browser following  URI
      http://127.0.0.1:5000/getData
  - Output :- you will get response in json formate 
  
  
 # Note :-
     -   1> Assignment 1 :- AS01.py
     -   2> Assignment 2 :- ASG02_REST_API.py
