# Notes: ML in JupyterLab 

## Installation 

Install jupyter-lab: 
```
pip install jupyter-lab
```

Run with: 
```
jupyter-lab
```


Install Virtualenv 
```
pip install virtualenv 
```

Create venv: 
```
python -m venv venv 
```

Note, on windows to activate might need to set execution policy in powershell to:
```Set-ExecutionPolicy Unrestricted -Scope Process```
Activate: 
```
.\venv\Scripts\activate
```

Register venv with jupyter-labs: 
```
pip install ipykernel
python -m ipykernel install --user --name=<my_env_name>
```
Then select the virtualenv as the kernel in jupyter-labs. 

### Install Python Dependancies 

```
$ virtualenv <env_name>
$ source <env_name>/bin/activate
(<env_name>) $ pip install -r path/to/requirements.txt
```