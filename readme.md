# Project Overview:
This application leverages facial recognition technology to manage and recognize individual identities through a web-based interface. It offers functionalities ranging from dataset creation to real-time face detection, empowering users to train a facial recognition model tailored to their needs.

## Setup steps
-- 1. First thing to download the zip file or 
use below command to clone the project 
```
git clone https://github.com/rrrreddy/Facerecognition_python_django.git
```
-- 2. create the virtual envirnment and activate it
	virtualenv env
```
	 source env/bin/activate
```
-- 3. Installing the dependencies
```
	pip install -r requirements.txt
```
-- 4. Note the (env) in front of the prompt. This indicates that this terminal session operates in a virtual environment set up.




## How to run the project:

Once the setup is complete, you can run the project with the following steps:

```
	cd Facerecognition_python_django
	python manage.py runserver
```
#### Launch the server:
```
http://127.0.0.1:8000
```


## Application Walkthrough:
The application interface provides four main functionalities:

### Create Dataset:

Select "Create Dataset" to initiate a popup for dataset ID input.
After ID submission, activate the camera to capture images, forming the dataset.

### Admin Panel:

Access the admin panel using:
Username: ```admin```
Password: ```admin```
Add and manage records related to the datasets through the admin interface.

### Train Classifier:

Post dataset creation and management, select "Train Classifier" to train the model on the new data.
Detection Mode:

Use "Detect by Webcam" to start the facial recognition process.
The system will identify registered faces and redirect to a details page for known individuals.
Unknown faces will be marked as "Unknown" directly on the live camera feed.
