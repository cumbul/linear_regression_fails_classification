# Linear Regression Fails Classification

## Code

This code shows why multiple linear regression cannot be used for problems needing classification methods with an example.
The code is written in Jupyter notebook, and to run the code, install python, create a virtual environment and include dependencies.


```
# install python
python3 -m pip install --user -U pip
python3 -m pip install --user -U virtualenv

#choose a path for project and add files in this repo
cd $path_you_choose

# create virtual environment and activate
python3 -m virtualenv my_env
source my_env/bin/activate # on Linux or macOS
.\my_env\Scripts\activate  # on Windows

# install dependencies
python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn
python3 -m ipykernel install --user --name=python3
```
Drag and drop ipynb file into path_you_choose
```
# start jupyter notebook
jupyter notebook
```
run code.
