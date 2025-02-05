### STEPS TO CREATE INDUSTRY STANDARD PYTHON MACHINE LEARNING
Create an environment
conda create -p venv python==3.8 -y

## Activate the conda environment
conda activate venv/

## Clone the Repository and Sync with Github
git init
git add README.md
git commit -m 'README'
git branch -M main
git remote add origin https://github.com/OluomaOji/generic_mlproject.git
git push -u origin main
create .gitignore from the Main Repository in python
git pull

## Create the Setup.py
The setup.py is responsible for creating the machine learning application as a package.
## Create the requirements.txt
Create the src folder