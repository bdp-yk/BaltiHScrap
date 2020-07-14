# requirements
- Python [latest versions are good]
# installation
- create new environment in this folder
```sh
python -m venv [virtual_environment_name]
```
- activate environment in this folder
```sh
.\[virtual_environment_name]\Scripts\activate
```
- install all dependecies
```sh
pip install -r requirements.txt
```
- set the flask properties
```sh
$env:FLASK_APP = "app.py" // this is optional
$env:FLASK_ENV = "development" // this is required
```
- run the application
```sh
flask run
```

## todo
- scrap custom date range
- export custom fields