# python-basics
Record some Python basics

## Virtual Environment

* Create a Python2 virtual environment (Use MacOS internal Python)
```commandline
virtualenv -p /usr/bin/python2.7 venv
```

* Create a Python3 virtual environment (Use external Python)
```commandline
virtualenv -p /usr/local/bin/python3.8 venv
```

* Install all requirement packages (if there is a requirements.txt)
```commandline
pip install -r requirements.txt
```

* Activate the virtual environment
```commandline
source venv/bin/python
```

* Deactivate
```commandline
deactivate
```
