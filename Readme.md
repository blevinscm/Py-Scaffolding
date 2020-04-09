Python Scaffolding as a starting point
=============================================================================

![GitHub](https://img.shields.io/github/license/blevinscm/Py-Scaffolding) 
![GitHub release](https://img.shields.io/github/release/blevinscm/Py-Scaffolding?include_prereleases)

This repository contains the source code to create a change subsription webhook on a SharePoint document library by calling the SP API and then receive the changes to a local flask webapp and parsing the JSON. 


## Setup virtual environment (Windows)
https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

Within powershell or your shell of choice

1. Make sure venv is installed globally
    ```bash
    py -m pip install --user virtualenv
    ```
2. cd into workspace
    ```PS
    cd \[repo]\
3. Create virtual environment
    ```PS
    py -m venv spenv
    ```
4. Activate virtual environment
    ```ps
    spenv\Scripts\activate
    ```
5. Install pip dependencies
    ```ps
    pip install -r requirements.txt
    ```
6. CD into configuration

7. Set variables in config.py

8. Run 
    ```ps
    py lib
    ```
9. Output will be in output folder

9. To get out of venv
    ```ps
    deactivate
    ```
