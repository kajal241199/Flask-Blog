# Flask-Blog
Tagline
***
Local Installation Guide:
---
* **Clone Repository**
```
git clone https://github.com/kajal241199/Flask-Blog.git
```
* **Go to the Working directory**
```
cd Flask-Blog
```
* **Install the virtual environment**
```
python -m pip install --user virtualenv
python -m virtualenv --help
```
* **Activate the virtual environment**
```
fblog\Scripts\activate
# or 
cd fblog
cd Scripts\activate
```
* **Deactivate the virtual environment**
```
deactivate
```
* **Installing dependencies in virtual environmnet with pip**
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
Registration Page
<img src="https://user-images.githubusercontent.com/42913243/109532414-1c897c00-7adf-11eb-84bf-40c448a2d543.png" />
Login Page
<img src="https://user-images.githubusercontent.com/42913243/109533187-f57f7a00-7adf-11eb-870f-3484dbdf06a6.png" />
Home Page
<img src="https://user-images.githubusercontent.com/42913243/109533547-5c049800-7ae0-11eb-8036-e5e330faa8ff.png" />










