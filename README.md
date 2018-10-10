# ADC for ASPAM project

This ADC serves for work with ASPAM project. 

It has N channels for Hall-effect based turn counter. 
It has M channels for 5V general analog sensors as well.

Hall-effect based turn counter works as following: 
* the rotating disk contains to magnets that intercepts the sensors
* when magnet is near the sensor its magnetization vector is directed to sensor (m1) 
   or to the opposite direction (m2)
* when m1 approach the sensor it gives logical unity and keeps it until m2 comes
* when m2 approach the sensor it gives logical zero and keeps it until m1 comes

The described behavior is implemented in SS41 Bipoloar (Honeywell).

The board contains XLR plugs and the mounting place for STM32 (Mapple Mini).

# ASPAM Project

This ADC is natural part of ASPAM project.

https://github.com/comcon1/ASPAM

# Licensing 

The project "Automated Spontaneous Physical Activity Monitoring" 
(A. Nesterenko, I. Kuzmin, P. Mamonov)  
is released under  license CC BY-SA 3.0.
