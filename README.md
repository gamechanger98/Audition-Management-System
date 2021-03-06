# Audition Management System

> This app is basically used to keep track of the audition statistics and reviews , generate results automatically and thus resulting in a hassle free auditioning experience.

[![CircleCI](https://circleci.com/gh/JayjeetAtGithub/Audition-Management-System.svg?style=svg)](https://circleci.com/gh/JayjeetAtGithub/Audition-Management-System)

[![gsocheat](https://img.shields.io/badge/GSoC%20Heat-2019-orange.svg)](https://nitdgpos.github.io/gsoc_heat)


##  Building From Source 


* Fork and Clone the repository
```
https://github.com/<your_github_handle>/Audition-Management-System.git

```

* Create a virtualenv with python 3 and activate it
```
virtualenv --python=/usr/bin/python3 venv3

source venv3/bin/activate
```

* Move into the folder and install dependencies
```
cd Audition-Management-Portal

pip install -r requirements.txt
```

* Run the development server and navigate to http://localhost:8000
```
python manage.py makemigrations

python manage.py migrate

python manage.py runserver

```

## How to Contribute ?

* You may solve an annoying bug 
* You may add some cool feature
* You may open any issue or request some nice features

Please head over to [Contribution Guidelines](https://github.com/JayjeetAtGithub/Audition-Management-System/blob/master/CONTRIBUTING.md)


## Contributors 

* [Jayjeet Chakraborty](https://github.com/JayjeetAtGithub)
