# QM-Homework

This is a Jupyter Notebook project.

## To run the code

0. Make sure that 'anonymized_project.json' and 'references.json' are in the project directory.

1. `cd` to the project directory.

2. Create and activate virtual environment:
`python3 -m venv <my_env_name>`
`source <my_env_name>/bin/activate`

2. Install requirements in the current environment:
`pip3 install -r requirements.txt`

3. Add current environment to Jupyter:
`python3 -m ipykernel install --user --name=<my_env_name>`

4. Launch Jupyter Notebook:
`jupyter-notebook`

5. Open QM-Homework.ipynb and change kernel to `<my_env_name>`.

6. Click on 'kernel' and 'run all'.

## To stop Jupyter Notebook

`Ctrl + C`

## To export notebook as presentation slides and launch the slides

`jupyter nbconvert QM-Homework.ipynb --to slides --TemplateExporter.exclude_input=True --post serve`

## To deactivate virtual environment

`deactivate`

## To remove virtual environment 

`sudo rm -rf <my_env_name>`

## To uninstall kernel

`jupyter kernelspec uninstall <my_env_name>`
