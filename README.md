## Basic Flask blog app with jinja2 as rendering engine
### Installation
Clone the repo.
```
cd flask-blog
```
Create a virtual env and install the required dependancies.
```
python3 -m venv flask-blog-env
source flask-blog-env/bin/activate
pip install -r requirements.tx
```
Then, create the required migrations:

```
flask db init
flask db migrate
flask db upgrade
```
Then run the app
```
python3 app.py
```
Run the website on http://localhost:5000

