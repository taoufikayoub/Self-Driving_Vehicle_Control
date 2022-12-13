<div id="top"></div>

<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

</div>

</br>

<div align="center">
  <a href="https://github.com/taoufikayoub/BlindSupportApp">
    <img src="images/self-driving.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Self Driving Vehicle Control</h3>

  <p align="center">
    Implementation of a longitudinal and lateral controller in python for the CARLA simulator.
    <br />
    <a href="https://github.com/taoufikayoub/BlindSupportApp"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/taoufikayoub/BlindSupportApp">View Demo</a>
    ·
    <a href="https://github.com/taoufikayoub/BlindSupportApp/issues">Report Bug</a>
    ·
    <a href="https://github.com/taoufikayoub/BlindSupportApp/issues">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#how-to-install-the-ml-server">Server Installation</a></li>
        <li><a href="#how-to-install-the-mobile-app">Mobile App Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

This project was part of the Self-Driving Cars Specialization by the University of Toronto on Coursera.
The goal is to control the vehicle to follow a race track by navigating through preset waypoints, and test and validate the results on CARLA's 3D environnement and matplotlib graphs. 

### Control Technologies used

Longitudinal control:
- [PID Control](https://en.wikipedia.org/wiki/PID_controller)

Lateral control:
- [Stanley Control](https://en.wikipedia.org/wiki/Stanley_(vehicle))

<p align="right">(<a href="#top">back to top</a>)</p>

## Demo

These are the results of running the simulation with the given course inputs.

### CARLA Simulation Environment

<img src="images/CARLA_Simulation.png" alt="CARLA Simulation">

### Controls Feedback & Trajectory trace

<img src="images/Controls_Trajectory.png" alt="Control Feedbacks and Trajectory">

<p align="right">(<a href="#top">back to top</a>)</p>

## How to run

Please follow these instructions:

1) Follow the CARLA Installation guide HERE to install the CARLA simulator

2) Move the folder "Vehicle_Control" folder into the subfolder folder "PythonClient" inside the "CarlaSimulator" (root) folder.

3) Run module_7.py

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/taoufikayoub/BlindSupportApp.svg?style=for-the-badge
[contributors-url]: https://github.com/taoufikayoub/BlindSupportApp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/taoufikayoub/BlindSupportApp.svg?style=for-the-badge
[forks-url]: https://github.com/taoufikayoub/BlindSupportApp/network/members
[stars-shield]: https://img.shields.io/github/stars/taoufikayoub/BlindSupportApp.svg?style=for-the-badge
[stars-url]: https://github.com/taoufikayoub/BlindSupportApp/stargazers
[issues-shield]: https://img.shields.io/github/issues/taoufikayoub/BlindSupportApp.svg?style=for-the-badge
[issues-url]: https://github.com/taoufikayoub/BlindSupportApp/issues
[license-shield]: https://img.shields.io/github/license/taoufikayoub/BlindSupportApp.svg?style=for-the-badge
[license-url]: https://github.com/taoufikayoub/BlindSupportApp/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/taoufik-ayoub
[product-screenshot]: images/screenshot.png
