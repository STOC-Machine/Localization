# Localization

*This is the localization repo from the team for mission 8.*

## Requirements
Inertial: Python 3, scipy, numpy (currently installed from pip)

## Inertial
This is attempting to use physics to determine our location from known attitude and altitude. It uses 
those values to determine a force IVP, then uses an ODE solver to find the drone's velocity and position.
