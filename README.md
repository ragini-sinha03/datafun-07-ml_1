# datafun-07-ml_1

### This project 7 will use Supervised Machine learning to create a linear regression model for a data set and then use that model to make predictions. 

## Created a project and cloned it to machine

##### I creatred a new repository on GitHub. 
##### I made sure that the README.md to document the process. 
##### I then went to a folder on my computer, where I wanted to file to keep, and I opened the terminal for that file.
##### I then cloned the repository to that folder using the following command:


git clone site_URL


## Added files 

##### I added a .py file to work in, requirements.txt to hold the required project modules, a .vinv to act as the virtual environment(instructions for that are below), and a .gitignore to hold the .venv and the .vsode file so that the virtual environment is not passed to the rest of the python environment.

## Created Virtual Environment for the project

##### I created a project virtual environment in the .venv folder. 


#creates .venv file then activates it
py -m venv .venv
.venv\Scripts\Activate


## Installed all the required packages into local project virtual environment

##### This installs the required packages that are held in the requirements.txt file - requests 



#installs all files in requirements.txt
py -m pip install -r requirements.txt

## Git add and commit 

##### I add, commit and push the file to the web periodically.

git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
