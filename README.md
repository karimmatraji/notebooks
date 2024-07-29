## Hello!

## Overview
The Seismic Data Lake project aims to create a comprehensive data repository for the seismology and earth sciences domain. This data lake integrates data, models, and accumulated knowledge, facilitating the curation, maintenance, and exploration of diverse data collections. The objective is to provide methods for navigating and enriching these collections, enabling the generation of new data and analytical insights.

## System Architecture
The system architecture comprises the following key components:
- **Data Ingestion**: Processes for importing data into the data lake.
- **Metadata Management**: A metadata model for organizing and describing data.
- **Data Storage**: Utilizes PostgreSQL for structured data storage.
- **Web Interface**: A Flask-based web application for user interaction and data visualization.

## Main Functions and Features
- **Data Ingestion and Processing**: Tools for importing and preprocessing seismological data.
- **Metadata Management**: A comprehensive model for managing metadata associated with data sets.
- **Data Analysis and Visualization**: Features for analyzing data and visualizing results.
- **User Interface**: A web-based interface for accessing and interacting with the data lake.

## Directory Structure and Contents
- **data/**: Contains CSV files required for the project.
- **docs/**: Includes documentation related to the project.
- **notebooks/**: Jupyter notebooks for initializing the database and inserting data.
- **src/**: Source code for the demo web application.

## Setup and Installation
### Prerequisites
- Python 3.x
- PostgreSQL
- Flask
- JupyterLab

## How to use the code:
### For the code in the notebooks folder:
First of all, ensure that jupyterlab is installed:

> pip install jupyterlab

Next, open a terminal in the ./notebooks/ directory and launch a jupyter lab there using:

> jupyter lab

you will get a bunch of log output in the terminal.
Please ensure that the port 8888 is not used by anything else on your machine.

Now, among the log files, you will find the following:

> Or copy and paste one of these URLs:
>        http://localhost:8888/lab?token=<token>
>        http://127.0.0.1:8888/lab?token=<token>

Now you can navigate to any of the juputer notebooks and run the code in the kernel.

### For the code in the src folder:
download all requirements in the requirements text file.
This can easily be done by using the -r tag with the pip command.

First of all, open the a terminal session in the ./src/ directory.

Then, execute:

> pip -r install requirements.txt

Then, you can run the demo web application using:

> python3 Updated_Demo.py
Note: the use of python, python3, py, py3, pip, pip3, etc... relies solely on your specific operating system and python installation.

