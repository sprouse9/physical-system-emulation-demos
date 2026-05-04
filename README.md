# Physical System Emulation Demos

Small MATLAB/Simulink modeling projects exploring simplified physical-system emulation, signal flow, operating limits, logging, and visualization.

These are educational toy models designed to practice Simulink modeling, physical-system assumptions, test-style documentation, and iterative model development.

## Projects

### Wind Turbine Power Simulation

A MATLAB/Simulink model that estimates wind turbine power output from wind speed, applies cut-in/cut-out logic, caps output at rated power, and integrates power over time to estimate accumulated energy.

[Open the wind turbine project](wind_turbine/)

## Planned Projects

### Electric Outboard Motor / Load Emulator

Planned simplified model for throttle input, motor torque, propeller load, RPM response, current draw, thermal behavior, and load-condition changes.

### Mass-Spring-Damper Demo

Planned starter physical-system model for displacement, velocity, acceleration, spring force, damping, and external force response.

## Purpose

The goal of this repository is to demonstrate hands-on modeling and simulation practice using MATLAB/Simulink-style workflows:

- define simplifying assumptions
- create a physical model
- run a repeatable simulation
- visualize signals using scopes
- document outputs and future improvements

The models use safe simplified parameters and are not based on proprietary, classified, or production systems.
