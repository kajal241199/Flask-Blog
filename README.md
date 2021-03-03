# Flask-Blog
Flask-Blog is a blog website built using Flask
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
* **Install the dependencies**
```
pip install -r requirements.txt
```
* **To list the installed packages**
```
pip freeze
```
* **Deactivate the virtual environment**
```
deactivate
```
# Build Databse
```
python
>> from flaskblog import db
>> db.create_all()
>> exit()
```
## Set Username and password 
* **Set Username and password for sending link to change password**
```bash
 1. Go in search and write enviroment varible and click on edit the system envrioment varible
 2. Now got to Enviroment varible option
 3. now set two system varible:-
   a. EMAIL_USER as varible name and <a valid gmail id> as varible value
   b. EMAIL_PASSWORD as varible name and <a valid gmail password> as varible value
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
Account Page for Updating Account Information
<img src="https://user-images.githubusercontent.com/42913243/109533945-ccabb480-7ae0-11eb-9c4e-7245a689ca81.png" />
Password Reset Link sent on the user's email
<img src="https://user-images.githubusercontent.com/42913243/109534939-ed283e80-7ae1-11eb-8332-d7d6738cdd63.png" />
Reset Password Page
<img src="https://user-images.githubusercontent.com/42913243/109535351-7b042980-7ae2-11eb-829b-4be3e11d0afa.png" />
User is now able to login with the updated password
<img src="https://user-images.githubusercontent.com/42913243/109535675-d7674900-7ae2-11eb-84e8-bce93d36ca0b.png" />
Page for adding New Post
<img src="https://user-images.githubusercontent.com/42913243/109535901-1a292100-7ae3-11eb-9188-4880613a8f7f.png" />










