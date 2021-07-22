# QM-Homework

This is a Jupyter Notebook project.

## Contents
1. [Run the code](#1-run-the-code)
2. [Stop Jupyter Notebook](#2-stop-jupyter-notebook)
3. [Export notebook as presentation slides](#3-export-notebook-as-presentation-slides)
4. [Deactivate virtual environment](#4-deactivate-virtual-environment)
5. [Remove virtual environment](#5-remove-virtual-environment)
6. [Uninstall kernel](#6-uninstall-kernel)


## 1. Run the code

**Make sure that 'anonymized_project.json' and 'references.json' are in the project directory before taking the following steps.**
1. `cd` to the project directory.
2. Create and activate virtual environment:

```bash
python3 -m venv <my_env_name>
source <my_env_name>/bin/activate
```
3. Install requirements in the current environment:

```bash
pip3 install -r requirements.txt
```
4. Add current environment to Jupyter:

```bash
python3 -m ipykernel install --user --name=<my_env_name>
```
5. Launch Jupyter Notebook:

```bash
jupyter-notebook
```
6. Open QM-Homework.ipynb and change kernel to `<my_env_name>`.
7. Click on 'kernel' and 'run all'.


## 2. Stop Jupyter Notebook

```bash
Ctrl + C
```


## 3. Export notebook as presentation slides

```bash
jupyter nbconvert QM-Homework.ipynb --to slides --TemplateExporter.exclude_input=True --post serve
```

## 4. Deactivate virtual environment

```bash
deactivate
```

## 5. Remove virtual environment 

```bash
sudo rm -rf <my_env_name>
````

## 6. Uninstall kernel

```bash
jupyter kernelspec uninstall <my_env_name>
```
