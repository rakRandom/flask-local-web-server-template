# Flask Local Web Server Template

Template for local web servers projects using Python with Flask.

This is just a basic local web server hosting made for fun, and it was not designed to be used as an business application.

## Step by step guide to use

### Setup a virtual environment (Optional):
``` cmd
python -m venv env
.\env\Scripts\activate
```

### Update pip (Optional):
``` cmd
python.exe -m pip install --upgrade pip
```

### Install the requirements:
``` cmd
pip install -r requirements.txt
```
or
```
pip install flask
```

### Start the Flask Server:
``` cmd
python app.py
```

### Test the template:
First you need to get your IPv4 number, you can get using this command on Windows:
``` cmd
ipconfig
```
and this command on Linux and Mac:
``` bash
ifconfig
```

Look for the code after "IPv4 Address" at your main adapter, then access the URL using your IPv4 code, see the example:
```
http://youripv4:8000
```

Test it preferably on another device, such as your smartphone, but make sure that it is connected to the same wi-fi as your host device.

## Licence
This repository is currently not under any [LICENCE](LICENCE)
