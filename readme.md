# Astrobee Robot Software - Multimedia

## About

Astrobee is a free-flying robot that is designed to operate as a payload inside
the International Space Station (ISS). The Astrobee Robot Software consists of
embedded (on-board) software, supporting tools and a simulator. The Astrobee
Robot Software operates on Astrobee's three internal single board computers and
uses the open-source Robot Operating System (ROS) framework as message-passing
middleware. The Astrobee Robot Software performs vision-based localization,
provides autonomous navigation, docking and perching, manages various sensors
and actuators, and supports user interaction via screen-based displays, light
signaling, and sound. The Astrobee Robot Software enables Astrobee to be
operated in multiple modes: plan-based task execution (command sequencing),
teleoperation, or autonomously through execution of hosted code uploaded by
project partners (guest science). The software simulator enables Astrobee Robot
Software to be evaluated without the need for robot hardware.

This repository provides multimedia used by Astrobee Robot Software, for both
visualizing experiments and simulating free-flyers. It includes meshes and
textures from the following two external sources:

* [IGOAL](https://nasa3d.arc.nasa.gov/detail/iss-internal) - ISS Interior.
* [RoboNaut2](https://gitlab.com/nasa-jsc-robotics/r2_gazebo) - ISS Handrails.

## Change Log

v0.0.4 : Improved handrail meshes and perching arm textures.
v0.0.3 : Restructured media to allow spawning certain models from world file.
v0.0.2 : Added granite lab mesh.
v0.0.1 : Added dock, space station, free-flyer and perching arm meshes.

## Usage Guidelines

The repository contains original multimedia created in the Astrobee project and
redistributed multimedia from other NASA projects. All multimedia is covered by
NASAs [Media Usage Guidelines](https://www.nasa.gov/multimedia/guidelines/index.html).

## Instructions

Setup instructions for the Astrobee Robot Software may be found on the
[official respository](https://github.com/nasa/astrobee).
