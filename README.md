<p align="center"><img src="ReadmeImages/header.png" width="100%"></p>

# TCM Broach Inspector

Multifunctional system for the automatic inspection of flat broaching tools, featuring:
* 2-stage AI-based image processing system (detection of tooth application surface and failure segmentation)
* 3D analysis system with laser profilometer
* Module for cost optimisation of the tool reconditioning process
* Dash based interactive application to view results, select the optimum regeneration method and generate a tool scan report
* TKinter based host application
* SQL database for storing the results of the performed scans

<p align="center"><img src="ReadmeImages/scanner.png"></p>

## General Information

- Jupiter notebooks with scripts for training and evaluation of AI models 
- Based on the ResNET architecture
- Annotations with detected artefacts saved in .json format, compatible with LabelMe software
- Supervised learning using customised datasets
- System for semi-automatic creation of datasets
- Proprietary evaluation methods with modified F1 metric
- Model comparison and performance tracking using Neptune.AI
- Results displayed in an interactive DASH-based application
- Cost optimisation module for tool regeneration strategy
- Input and output data stored in SQL database
- System for user authorisation, user account management and supervision of access to data and selected functionalities

## Technologies Used

- Python 3.7.0
- Detectron2 v0.6
- PyTorch 1.11.0
- Pandas 1.3.5
- OpenCv 4.5.1
- NumPy 1.21.3
- Dash 2.1.0
- Json 2.0.9
- NVIDIA CUDA 11.3

## Features

**Dash application used for output visualization.**
<p align="center"><img src="ReadmeImages/dash_app.png"></p>

**TKinter based host application with console output**
<p align="center"><img src="ReadmeImages/dash_host.png"></p>

**MLOPs platform - Neptune AI for experiments tracking pourposes.**
<p align="center"><img src="ReadmeImages/neptune.png"></p>

**Automatic labels in .json lableme compatible format, generated using detectron2 model inference.**
<p align="center"><img src="ReadmeImages/labelme.png"></p>


## Project Status

Project is: _in progress_ 

## Experiments trackingt

Neptune [click here](https://app.neptune.ai/kacper-marciniak/)

## Organisations involved in the project development

<div align=center><table>
  <tr>
    <th><a href="https://pwr.edu.pl/">Wrocław University of Science and Technology</a></th>
    <th><a href="https://mvlab.pl/">Machine Vision Laboratory]</a></th>
    <th><a href="https://www.tcm-international.com/">TCM International</a></th>
  </tr>
  <tr>
    <td width=33%><p align="center"><img src="ReadmeImages/pwr-logo.png" height="100"></p></td>
    <td width=33%><p align="center"><img src="ReadmeImages/mv-logo.png" height="100"></p></td>
    <td width=33%><p align="center"><img src="ReadmeImages/TCM-logo-text.png" height="75"></p></td>
  </tr>
</table></div>
