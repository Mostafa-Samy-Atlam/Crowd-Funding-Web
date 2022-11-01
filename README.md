# Crowd-Funding-Web
This is a project for crowd funding web page.a\
Steps to run the project:
	1- Download or Clone the project.
	2- Download or Clone the project (v.3 or above).
	3- install and upgrade pip:
		python -m pip install --upgrade pip
	4- Open the project in pycharm.
	5- In the terminal window of the IDE:
		a- install VirtualEnvironment.
			pip install virtualenv
		b- Create and Activate VirtualEnvironment
			virtualenv .venv
			for Windows:
				.venv\Scripts\activate
			for Linux:
				source .venv/bin/activate
	6- Install requirments
		pip install -r requirements.txt
	7- Set These Values in "setting.by" file to test Verification using email: ( add your [gmail] but insure that the account security not activated)
		EMAIL_USE_TLS = True
		EMAIL_HOST = 'smtp.gmail.com'
		EMAIL_HOST_USER = 'example@gmail.com'
		EMAIL_HOST_PASSWORD = 'example*'
		EMAIL_PORT = 587
	8- 
