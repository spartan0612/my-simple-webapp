# my-simple-webapp

This is a simple web application using Python Flask.
   
## 1. Install all required dependencies
  
  Python and its dependencies

    apt-get install -y python python-pip 

   
## 2. Install and Configure Web Server

Install Python Flask dependency

    pip install flask

- Copy app.py or download it from source repository

## 3. Start Web Server

Start web server

    FLASK_APP=app.py flask run --host=0.0.0.0
    
## 4. Test

Open a browser and go to URL

    http://<IP>:5000                            => Welcome