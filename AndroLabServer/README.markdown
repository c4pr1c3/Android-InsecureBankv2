AndroLab Back-end Server Readme
==========

This project is the python2 backend server for the Android InsecureBankv2 application which can be found at https://github.com/dineshshetty/Android-InsecureBankv2


Python required libraries
-----

Install the below libraries using: easy_install <libraryname>

* flask
* flask-sqlalchemy
* simplejson
* cherrypy
* web.py

Alternatively just use:

```bash
# https://github.com/pypa/pipenv
pipenv install -r requirements.txt --two

# 国内用户推荐使用以下命令（使用清华 pypi 镜像源加速）
pipenv install

# 进入 pipenv 环境
pipenv shell
```

Running the python server
-----
Make sure you have python2 installed. Change the current directory to the AndroLabServer folder

	cd AndroLabServer

Use the below syntax to run the HTTP server

	python app.py

Use the below syntax to view the possible arguments

	python app.py --help
