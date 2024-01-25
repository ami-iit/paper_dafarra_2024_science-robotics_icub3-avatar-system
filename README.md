
<h1 align="center">
iCub3 Avatar System
</h1>

<h2 align="center"> Enabling Remote Fully-Immersive Embodiment of Humanoid Robots </h3>
<div align="center">
Stefano Dafarra, Ugo Pattacini, Giulio Romualdi, Lorenzo Rapetti, Riccardo Grieco, Kourosh Darvish, Gianluca Milani, Enrico Valli, Ines Sorrentino, Paolo Maria Viceconte, Alessandro Scalzo, Silvio Traversaro, Carlotta Sartore, Mohamed Elobaid, Nuno Guedelha, Connor Herron, Alexander Leonessa, Francesco Draicchio, Giorgio Metta, Marco Maggiali, Daniele Pucci
</div>


<div align="center">

https://github.com/ami-iit/paper_dafarra_2024_science-robotics_icub3-avatar-system/assets/18591940/37e23013-f13f-463e-b1e1-d5a84495b81e

</div>

<div align="center">
2024 Science Robotics
</div>
 
<div align="center">
  <a href="https://www.science.org/doi/10.1126/scirobotics.adh3834"><b>Science Robotics</b></a> | <!-- TODO: Add link -->
  <a href="https://arxiv.org/abs/2203.06972"><b>arXiv</b></a> |
  <a href="https://youtu.be/z0aoTzdx25Y"><b>YouTube</b></a>
</div>

## Architecture
![teleoperationSystemTake2](https://github.com/ami-iit/paper_dafarra_2024_science-robotics_icub3-avatar-system/assets/18591940/a6a726c0-4372-46e0-8f33-5c3d554d86e6)

## Code
The code used to perform the teleoperation experiments exploits the following open-source repositories:
- [`bipedal-locomotion-framework`](https://github.com/dic-iit/bipedal-locomotion-framework)
- [`human-dynamics-estimation`](https://github.com/robotology/human-dynamics-estimation)
- [`ICUB`](https://github.com/robotology/icub-main)
- [`ICUBcontrib`](https://github.com/robotology/icub-contrib-common)
- [`icub-models`](https://github.com/robotology/icub-models)
- [`iDynTree`](https://github.com/robotology/idyntree)
- [`matioCpp`](https://github.com/dic-iit/matio-cpp)
- [`robometry`](https://github.com/robotology/robometry)
- [`robot-log-visualizer`](https://github.com/ami-iit/robot-log-visualizer)
- [`robots-configurations`](https://github.com/robotology/robots-configuration)
- [`walking-controllers`](https://github.com/robotology/walking-controllers)
- [`walking-teleoperation`](https://github.com/robotology/walking-teleoperation)
- [`wearables`](https://github.com/robotology/wearables)
- [`YARP`](https://github.com/robotology/yarp)
- [`yarp-device-openxrheadset`](https://github.com/ami-iit/yarp-device-openxrheadset)
- [`yarp-openmct`](https://github.com/ami-iit/yarp-openmct)

These can be installed by using the [`robotology-superbuild`](https://github.com/robotology/robotology-superbuild), enabling the following options
- `ROBOTOLOGY_ENABLE_CORE`
- `ROBOTOLOGY_ENABLE_DYNAMICS`
- `ROBOTOLOGY_ENABLE_DYNAMICS_FULL_DEPS`
- `ROBOTOLOGY_ENABLE_TELEOPERATION`
- `ROBOTOLOGY_ENABLE_HUMAN_DYNAMICS`
- `ROBOTOLOGY_USES_PYTHON`

## Generate the paper figures

It is possible to generate the paper's figures by running [this MATLAB script](https://github.com/ami-iit/icub3-avatar-system-paper-data/blob/159dc523383e3cda9a4f214e52271b9a26a0e12d/generate_plots/generate_plots.m).

## Citing this work

If you find the work useful, please consider citing:

```bib
@article{dafarra2024icub3,
author = {Stefano Dafarra  and Ugo Pattacini  and Giulio Romualdi  and Lorenzo Rapetti  and Riccardo Grieco  and Kourosh Darvish  and Gianluca Milani  and Enrico Valli  and Ines Sorrentino  and Paolo Maria Viceconte  and Alessandro Scalzo  and Silvio Traversaro  and Carlotta Sartore  and Mohamed Elobaid  and Nuno Guedelha  and Connor Herron  and Alexander Leonessa  and Francesco Draicchio  and Giorgio Metta  and Marco Maggiali  and Daniele Pucci },
title = {iCub3 avatar system: Enabling remote fully immersive embodiment of humanoid robots},
journal = {Science Robotics},
volume = {9},
number = {86},
pages = {eadh3834},
year = {2024},
doi = {10.1126/scirobotics.adh3834},
URL = {https://www.science.org/doi/abs/10.1126/scirobotics.adh3834},
eprint = {https://www.science.org/doi/pdf/10.1126/scirobotics.adh3834}}
```



## Maintainer

This repository is maintained by:

|                                                              |                                                      |
| :----------------------------------------------------------: | :--------------------------------------------------: |
| [<img src="https://github.com/S-Dafarra.png" width="40">](https://github.com/S-Dafarra) | [@S-Dafarra](https://github.com/S-Dafarra) |
