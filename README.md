# CMD Cheatsheet
Windows Command Prompt Cheatsheet for Python Development

### General commands

`cls`: Clears the screen.

`mkdir`:Opens a folder in a current directory.

`echo >>`: Creates file in a current directory or folder.

`del /f fileName`: Deletes the file named fileName.

### Navigating between directories and directory commands

`cd`: Changes the directory.

`cd/`: Goes into root directory.

`cd..`: Goes up to one directory level.

`cd../..`: Goes up to two directory level.

`cd-`: Goes up to previous directory.

`dir`: Shows what is inside the current directory.

`dir/w`:Shows what is inside the current directory (side by side).

### Creating venv and uploading requirements

`python -m venv venv`: Creates the virtual enviroment. (Second venv is the name of the virtual environment, you can choose whatever name you want.)

`venv\Scripts\activate`: Activates the virtual enviroment.

`pip list`: All of the python packages that is currently installed in the enviroment. 

If the virtual environment is newly created it should contain only **pip** and **setuptools**. If there are other packages, it means that the virtual environment could not be created correctly.

`venv\Scripts\deactivate`: Deactivates the virtual enviroment.

`pip install -r /path/requirements.txt`: Installs recommended versions into the virtual environment.

### Creating venv in jupyter notebook

`pip install ipykernel`: Let us create new kernels for jupyter notebook.

`ipython kernel install --user --name=venvkernel`: Creates kernel named venvkernel.

`pip freeze`: Shows information about each package.

### Git commands

`git init`: Initializing empty git repository.

`git add .`: All changes are added to git.

`git status`: Gives information about the current status of the project files. Shows files whose status has been changed.

`git commit -m "first commit"`: Ready for commit. ("information about commit in here")

`git branch branchName`: Opens a new branch called branchName.

`git checkout`: Allow transition between branches.

`git push -u origin branchName`: Pushes changes into branch branchName.

`echo #Readme > README.md`: Gives markdown title (Readme) for README.md
