# ACar
Autonomous driving RC model car

# About
The goal is the development of an autonomous driving RC model car.  
The car itself is not part of the development.  
- STM32 Discovery board
- doughter board for connectors
- MATLAB Simulink controller / governor

# Current state
Planning phase. No development startet yet.

# Project goals
- [ ] hardware platform (STM32 Discovery)
  - [ ] choose a Discovery board
  - [ ] decide which Simulink code generator to use
- [ ] doughter board (connectors, GPS)
  - [ ] schematics
  - [ ] layout routing
  - [ ] order + testing
- [ ] MATLAB Simulink
  - [ ] data input from sensors
  - [ ] data output to servos and cruise control
  - [ ] governors for distance control
    - [ ] keep distance to side
    - [ ] keep distance to front and rear
    - [ ] automatic turn when in front of wall
  - [ ] governors for autonomous driving
    - [ ] drive straight to GPS point