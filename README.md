<p align="center"><img src="ReadmeImages/header.png" width="100%"></p>

# TCM Broach Inspector

## General information

Multifunctional system for the automatic inspection of flat broaching tools, featuring:
* **2-stage AI-based image processing system** (detection of tooth application surface followed by failure segmentation)
* **3D analysis system** with laser profilometer (measurement of tooth height and detection of surface defects)
* **Module for cost optimisation** of the tool reconditioning process (selection of a regeneration method that maximizes overall profit over the tool's life cycle)
* Dash based **interactive application** to view results, select the optimum regeneration method and generate a tool scan report
* **SQL database** for storing the results of the performed scans

<p align="center"><img src="ReadmeImages/scanner.png"></p>

## Machine learning solutions

- **Detectron2 models** based on the ResNET architecture
- Supervised learning using **custom datasets**
- Annotations with artifacts saved in .json format, compatible with **LabelMe software**
- System for **semi-automatic datasets creation**
- Jupiter notebooks with scripts for training and evaluation of AI models 
- Proprietary evaluation methods with modified F1 metric
- Model comparison and performance tracking using **Neptune.AI**
- System for **AI errors reporting** (MLOps)

## Technologies used

- Python 3.10
- Detectron2 v0.6
- PyTorch 1.12
- NVIDIA CUDA 11.7

## Features

### Visualization application

**Broach wear map.**
<p align="center"><img src="ReadmeImages/broach_map.png"></p>

**Wear analysis for broach rows.**
<p align="center"><img src="ReadmeImages/broach_barplots.png"></p>

**Preview of apposition surface and detected artifacts.**
<p align="center"><img src="ReadmeImages/broach_toothpreview.png"></p>

**TKinter based host application with console output**
<p align="center"><img src="ReadmeImages/dash_host.png"></p>

### ML solutions

**MLOPs platform - Neptune AI for experiments tracking pourposes.**
<p align="center"><img src="ReadmeImages/neptune.png"></p>

**Automatic labels in .json lableme compatible format, generated using detectron2 model inference.**
<p align="center"><img src="ReadmeImages/labelme.png"></p>


## Project Status

Project is: _in progress_ 

## Organisations involved in the project development

<div align=center><table>
  <tr>
    <th><a href="https://pwr.edu.pl/">Wrocław University of Science and Technology</a></th>
    <th><a href="https://mvlab.pl/">Machine Vision Laboratory</a></th>
    <th><a href="https://www.tcm-international.com/">TCM International</a></th>
  </tr>
  <tr>
    <td width=33%><p align="center"><img src="ReadmeImages/pwr-logo.png" height="100"></p></td>
    <td width=33%><p align="center"><img src="ReadmeImages/mv-logo.png" height="100"></p></td>
    <td width=33%><p align="center"><img src="ReadmeImages/TCM-logo-text.png" height="75"></p></td>
  </tr>
</table></div>
