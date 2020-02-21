# A set of scripts to manage the DIT ELK stack

## Set up

1. create and activate a python 3x virtual env: `virtualenv --python=python3 env; source env/bin/activate`

2. install dependencies `pip install requirements.txt` or via pip-tools: `pip install pip-tools; pip-sync`

## cf-log-drain-checker.py

This script reports cloudfoundry applications that dont have an active log drain


