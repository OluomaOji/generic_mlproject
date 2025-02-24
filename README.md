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

## SETUP.py and REQUIREMENTS.txt
Create the Setup.py
The setup.py is responsible for creating the machine learning application as a package.
Create the requirements.txt

## SRC FOLDER
Create the src folder
Create the Components Folder, Initialize it as a package so that it can be exported into other file locations
Create the data_ingestion.py file within the Components Folder
Create the data_transformation.py file within the Components Folder
Create the model_trainer.py file within the Components Folder
Create the pipeline folder within the src folder
create predict_pipeline.py file within the pipeline folder
create train_pipeline.py file within the pipeline folder
create utils.py for reading dataset from a database or read model into the cloud within the src folder
create logger.py file within the src folder
create exception.py file within the src folder

## CODE
Write a custom Exception **your choice**
Write a custom Logger
Write the EDA.ipynb
Write the Model_Selection.ipynb