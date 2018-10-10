# TCC for ASPAM project

This TCC (turn counter controller) serves for work with ASPAM project. 

It has 12 channels for Hall-effect based turn counter. It has 4 ADC channels for 5V general analog sensors as well (e.g. illuminance sensor, temperature sensor, etc).

Hall-effect based turn counter works as following:

* the rotating disk contains two magnets that toggle the sensor;
* the magnets are located at different sides of the rotating disk;
* the magnets are oriented to the outside by different poles;
* when “north pole” magnet approaches the sensor, it gives logical “1” and keep this level until “south pole” magnet comes.
* when “south pole” magnet approaches the sensor, it gives logical “0” and keep this level until “north pole” magnet comes.

The described behavior is implemented in SS41 Bipolar (Honeywell).

The board contains XLR plugs and the mounting place for STM32 board (Mapple Mini).


# ASPAM Project

This TCC is natural part of ASPAM project.

https://github.com/comcon1/ASPAM

# Licensing 

The project "Automated Spontaneous Physical Activity Monitoring" 
(A. Nesterenko, I. Kuzmin, P. Mamonov)  
is released under  license CC BY-SA 3.0.
