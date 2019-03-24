# Digipathos Plant Disease Image Database Downloader
This project is a downloader for the plant disease image database provided by EMBRAPA (Brazilian Agricultural Research Corporation). Further information on the database can be found in [this](https://doi.org/10.1016/j.biosystemseng.2018.05.013) paper.

## Requirements
You will need python 3.6 or higher installed.
Additionally, you will need the python module *requests*. If you haven't already installed it, install it with `pip install requests`.

## Installation
With [git](https://git-scm.com/downloads) installed, you can install the downloader with:
```
git clone https://github.com/georg-un/digipathos-plant-disease-img-db-downloader
cd digipathos-plant-disease-img-db-downloader
```

## Usage
To use the downloader, open a terminal in the project folder and run the following command:
```
python3.6 run.py
```

**Note:** You can tell the script to download only original or cropped images.<br/>
To download only original images use the command `python3.6 run.py original`.<br/>
To download only cropped images use the command `python3.6 run.py cropped`.
