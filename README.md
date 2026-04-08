# Simple Web Application

This is a simple web application using [Python Flask](http://flask.pocoo.org/).

  
  Below are the steps required to get this working on a base linux system.
  
  - **Install all required dependencies**
  - **Install and Configure Web Server**
  - **Start Web Server**
   
## 1. Install all required dependencies
  
  Install Python and its dependencies
  ```bash
  apt-get install -y python3 python3-pip python3-venv
  ```

## 2. Create a virtual environment and activate it

```bash
python3 -m venv myenv && source myenv/bin/activate
```

## 4. Install and Configure Web Server

Install Python Flask dependency
```bash
pip3 install flask
```

- Copy `app.py` or download it from a source repository

## 5. Start Web Server

Start web server
```bash
FLASK_APP=app.py flask run --host=0.0.0.0
```

## 6. Test

Open a browser and go to URL
```
http://<IP>:5000                            => Welcome
http://<IP>:5000/how%20are%20you            => I am good, how about you?
```
