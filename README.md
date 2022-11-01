# Crowd-Funding-Web
- This is a project for crowd funding web page.\
- Steps to run the project:\
	- Download or Clone the project.\
	- Download or Clone the project (v.3 or above).\
	- install and upgrade pip:\
		python -m pip install --upgrade pip\
	- Open the project in pycharm.\
	- In the terminal window of the IDE:\
		- install VirtualEnvironment.\
			pip install virtualenv\
		- Create and Activate VirtualEnvironment\
			- virtualenv .venv\
			- for Windows:\
				.venv\Scripts\activate\
			- for Linux:\
				source .venv/bin/activate\
	- Install requirments\
		- pip install -r requirements.txt\
	- Set These Values in "setting.by" file to test Verification using email: ( add your [gmail] but insure that the account security not activated)\
		EMAIL_USE_TLS = True\
		EMAIL_HOST = 'smtp.gmail.com'\
		EMAIL_HOST_USER = 'example@gmail.com'\
		EMAIL_HOST_PASSWORD = 'example'\
		EMAIL_PORT = 587\
	- Go to the following file:

	- Load the database:
		python manage.py makemigrations
		python manage.py migrate
