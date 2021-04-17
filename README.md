
# CMD Cheatsheet
Windows Command Prompt Cheatsheet for Python Development

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

`venv\Scripts\deactivate`: Deactivates the virtual enviroment.

`pip install -r /path/requirements.txt`: Installs recommended versions into the virtual environment.

### Creating venv in jupyter notebook

`pip install ipykernel`: Let us create new kernels for jupyter notebook.

`ipython kernel install --user --name=venvkernel`: Creates kernel named venvkernel.

`pip freeze`: Shows information about each package.
