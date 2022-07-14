![plot](ReadmeImages/header.png)

# Broach teeth detection, classification & segmentation, supervized learning 
> Machine vision development software utilized for inspection of the broach teeth. It presents 2 step inference.
> ROI is extracted from the images captured by the 2D camera using first model. Second moodel is responsible for failures detection and segmentation. 
> Results are displayed in the dedicated interactive application.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Experiments tracking](#experiments-tracking)


## General Information
- Contains jupyter notebooks for models development purpouses
- Implemented automatic failures annotations in .json format compatible with labelme
- Results displayed in dash-based interactive application
- Teeth sharpening strategy optimization
- Results stored in SQL database
- Automatic dataset creation
- Custom evaluation methods using modified F1-score
- Models comparing and results tracking using Neptune.AI

## Technologies Used
- Python 3.7.0
- Detectron2 v0.6
- PyTorch 1.11.0
- Pandas 1.3.5
- OpenCv 4.5.1
- NumPy 1.21.3
- Dash 2.1.0
- Json 2.0.9
- CUDA 11.3

## Features

**Dash application used for output visualization.**
>![plot](ReadmeImages/dash_app.png)

**TKinter based host application with console output**
>![plot](ReadmeImages/dash_host.png)

**MLOPs platform - Neptune AI for experiments tracking pourposes.**
>![plot](ReadmeImages/neptune.png)

**Automatic labels in .json lableme compatible format, generated using detectron2 model inference.**
>![plot](ReadmeImages/labelme.png)


## Project Status
Project is: _in progress_ 

## Room for Improvement

- Implementing optimization of the teeth sharpening strategy
- Changes to the GUI
- Implementing preview of 3D scan results

## Experiments tracking
Neptune [click here](https://app.neptune.ai/kacper-marciniak/)
