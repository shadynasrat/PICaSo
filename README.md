<div align="center">


# PICaSo: A Collaborative Robotics System for Inpainting on Physical Canvas Using Marker and Eraser

<br />

![UBUNTU](https://img.shields.io/badge/UBUNTU-20.04-orange?style=plastic&logo=ubuntu)
![python](https://img.shields.io/badge/python-3.9-blue?style=plastic&logo=python)
![ROS2](https://img.shields.io/badge/ROS-Noetic-white?style=plastic&logo=ros)

Project Page : [Click Here](https://shadynasrat.github.io/PICaSo/)

<img width="" alt="Graphiti-ts-small" src="https://github.com/shadynasrat/PICaSo_proj/blob/main/picaso/assets/picaso_logo.png">

<br />

</div>

# Abstract
The integration of robotics and artificial intelligence has paved the way for innovative solutions in various domains. This paper introduces PICaSo (Physical Inpainting on Canvas Solution), a pioneering robotic painting system driven by fine-tuned text-to-image models. Departing from conventional approaches, PICaSo harnesses the power of tailored text-to-image algorithms to interpret natural language prompts and execute precise artistic renderings on canvas. Users guide the process by furnishing descriptive text, specifying desired imagery and placement, empowering the robotic arm to autonomously translate these instructions into physical artworks. Our system's innovation lies in its effective translation of digital inpainting processes into physical actions. Leveraging our multi-tools gripper, capable of seamlessly switching between eraser and pen functions, enables to seamlessly execute detailed drawings on canvas while also providing the flexibility to erase and redo sections as required. This paper comprehensively outlines the capabilities of the proposed system, explores potential applications across various domains, and addresses technical challenges encountered during its development.

<br />

<p align="center">
    <img src="/docs/PICaSo_files/preview.gif" width="700px">   
</p>

<br />


# Overview
We edit on physical canvas and publish the waypoints to ros topic so integration with different robotic arms is easier.

# Installation
```
pip install -r requirements

python main.py
```





## bibtex
```
@inproceedings{PICaSo,
  author={Shady Nasrat, Jae-Bong Yi, Minseong Jo, and Seung-joon Yi},
  booktitle={2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={xxxx--xxxx},
  year={2024},
  organization={IEEE}
}
```
