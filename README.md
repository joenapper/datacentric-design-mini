# Task manager app
## Datacentric mini-project

pip3 install flask

pip3 freeze --local > requirements.txt

echo web: python app.py > Procfile

git push heroku master

heroku ps:scale web=1

heroku website - settings - reveal config vars
- IP
- PORT

pip3 install flask-pymongo

pip3 install dnspython