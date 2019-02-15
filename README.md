# UNIT9 test

Test for encourage Unit9 people to hire me! (wink)

## Run the example with docker
```bash
cd docker
sh build.sh
sh run.sh
# After this, point your browser to http://localhost:5000/api
```

## Run the application locally

### Create your virtualenv and run the source
```bash
python -m venv ~/.virtualenv/unit9
. ~/virtualenv/unit9/bin/activate
pip install -r requirements.txt
. source.me
python src/main.py
# After this, point your browser to http://localhost:5000/api
```

## Run the application by installing it

### Create your virtualenv and install the application
```bash
python -m venv ~/.virtualenv/unit9
. ~/virtualenv/unit9/bin/activate
python setup.py install
unit9
# After this, point your browser to http://localhost:5000/api
```
