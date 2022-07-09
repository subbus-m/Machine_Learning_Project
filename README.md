# Machine_Learning_Project
This is machine learning project.

## Start Machine Learning Project.

### Software and account Requirement.

1. Github Account (https://github.com)
2. Heroku Account (https://dashboard.heroku.com/login)
3. VS Code IDE (https://code.visualstudio.com/download)
4. GIT Cli (https://git-scm.com/downloads)

Creating conda environment
```
conda create -p <env_name>
$conda create -p venv python == 3.7 -y
-y = yes, python version 3.7
-p --> create virtual environment in the path we are in
Create the environment always from command prompt (terminal) not to have issues with and then use Bash terminal to activate and others.
If any issues try giving complete path of the environment created
```

Activate the environment
```
conda activate venv/
```
OR
```
conda activate venv
```
OR
```
source activate venv
```

Install the requirements.txt
```
pip install -r requirements.txt
```

Any folders or files to be ignored to be uploaded to GIT, we need to mention them in .gitignore file

Environment folder created by us is not required to be uploaded to GIT.
So this VENV is mentioned in .gitignore file.

Once app.py file is created with code, we need to push the code to GIT. Below are the commands to push the files to GIT

Push using file names
```
git add file1 file2 .. filen
```

To push all the files from the location
```
git add .
```

To push only one file
```
git add <filename>
```

To ignore any of the files to be pushed to GIT, we need to add them in .gitignore so that they will not be added to GIT.

If we have added a file into GIT but the file is not added to GIT, then if we execute below command, we will get the status whether the file is added or not to the GIT
```
git status
```

To check all version maintained by git
```
git log
```

To create version/commit all changes by git
```
git commit -m 'message'
```

To send version/origin to github
```
git push origin main
```

To check remote url. The below command displays the origin where the current profile of Git represented.
```
git remote -v
```
