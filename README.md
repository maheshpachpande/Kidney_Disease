#### Create the venv
- python -m venv Kidney

#### activate the venv 
- C:\Users\user\Desktop\Kidney_Disease\Kidney\Scripts\activate.bat

#### create a new repository on the command line
- echo "# Kidney_Disease" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/maheshpachpande/Kidney_Disease.git
- git push -u origin main

#### create .gitignore(python) file in repository and pull in folder
git pull

#### push an existing repository from the command line
- git remote add origin https://github.com/maheshpachpande/Kidney_Disease.git
- git branch -M main
- git push -u origin main

#### template.py

#### setup.py

#### requirements.txt
- pip install -r requirements.txt

#### src/__init__.py  logger

#### utils common.py

#### dagshub
- MLFLOW_TRACKING_URI=https://dagshub.com/pachpandemahesh300/Kidney_Disease.mlflow \
- MLFLOW_TRACKING_USERNAME=pachpandemahesh300 \
- MLFLOW_TRACKING_PASSWORD=9f73334e82cb0e1dc7693e6eed2b0827c86e8db9 \
- python script.py

#### Run this to export as env variables:
- export MLFLOW_TRACKING_URI=https://dagshub.com/pachpandemahesh300/Kidney_Disease.mlflow

- export MLFLOW_TRACKING_USERNAME=pachpandemahesh300 

- export MLFLOW_TRACKING_PASSWORD=9f73334e82cb0e1dc7693e6eed2b0827c86e8db9

#### dvc
- dvc init
- dvc repro
#### Updating lock file 'dvc.lock'

#### To track the changes with git, run:

    - git add dvc.lock

#### To enable auto staging, run:

    - dvc config core.autostage true
##### Use `dvc push` to send your updates to remote storage.




