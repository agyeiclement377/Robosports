# EV3 Robot Tennis

This project programs two LEGO Mindstorms EV3 robots to autonomously play a game of tennis across a ramp "net". 

## Overview

- Uses MicroPython to control and program EV3 brick  
- Each robot equipped with a ball collector mechanism
- Vision sensor tracks ball 
- Most balls on side of court loses

## Robot Configuration

**Server Bot**

- Sweeper motor to take in the balls 
- Color sensor tracks when ball incoming

**Client** 

- Receives balls from Server bot
- Touch sensor trigger movement
- Moves balls to other side of the court


## Code Files

- `server.py` - Bot 1 program 
- `client.py` - Bot 2 program

## Improvements
 
- Optimized Sensing algorithms  
- Variable serves (power, angle etc)
- Omnidirectional Movement
