# Flask-Blog
Tagline
***
Local Installation Guide:
---
* Clone Repository
```
git clone https://github.com/kajal241199/Flask-Blog.git
```
* Go to the Working directory
```
cd Flask-Blog
```
* Install the virtual environment
```
python -m pip install --user virtualenv
python -m virtualenv --help
```
* Activate the virtual environmnet
```
fblog\Scripts\activate
# or 
cd fblog
cd Scripts\activate
```
* Installing dependencies in virtual environmnet with pip
```
pip install flask

pip install Flask-wtf

pip install flask-sqlalchemy

pip install flask-bcrypt

python -m pip install --upgrade pip // to update pip

python -m pip install --no-use-pep517 bcrypt // if bcrypt show error

pip install flask-login

pip install email_validator

pip install Pillow

pip install flask-mail

pip install flask-serialize
```
# Build Databse
```
python
>> from flaskblog import db
>> db.create_all()
>> exit()
```
# Run Project Locally in virtual Environment
```
python run.py
```






