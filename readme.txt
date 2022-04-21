Setup steps
1. First thing to download the zip file
2. create the virtual envirnment and activate it
	virtualenv env
	windows: 
	Ubutu: source env/bin/activate
3. Installing the dependencies
	pip install -r requirements.txt
4. Note the (env) in front of the prompt. This indicates that this terminal session operates in a virtual environment set up.




How to run the project:

Once pip has finished downloading the dependencies:
	cd Project
	python manage.py runserver
and navigate to http://127.0.0.1:8000



Walkthrough:
once we are in the url we can see 4 selectable options
1. Detect by webcam 
2. Train the classifier
3. Create Dataset
4. Admin panel
1. first step is to create a dataset, click on create dataset that will prompt an popup there we have to give an unique id for the dataset the one it's going to take
once we provided the id and submitted, camera will popup and take some random pictures of the person.
2. Now the data set is ready but we don't have any information related to that data set like to whowm the images are reffered to, for that click on admit panel and login to the admit portal
admin portal credentiols:
username: admin
password: admin
under records clikc on add new record and provide the information.
3. by the above step we are ready with the data set and information for it. now it's time to train our model for that just click on the tran model.
4. model is also trained now it's time for detection, click on detect by webcam camera will popup and it will look for human face if it know person is detected it will redirected to details page.
if an unknown person comes infornt of the camera on the camera screen itself it will shows us that unknow.


	
