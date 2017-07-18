# Term two::Project Five::MPC Control, - Write up report
## Files
The followong files are included in this solution:
```bash
main.cpp
MPC.cpp
MPC.h
```  
## MPC Control Reflection

The model takes the following states into account for the control:
* cars global position (`x, y coordinates`)
* speed in mph (`v`)
* yaw, heading direction (`psi`)
* 

_Actuators_
* throttle (scalar)
* steering angle (scalar, deg)

The actuation of the controls is delayed with a 100 ms latency in order to account for a realistic actuation model. 

_Path_
The controller aims at keeping the car on the way path represented by the waypoints, that is an ordered list of x and y coordinates in the global coordinate system. The waypoints represent a drivable path in the simulator.

## Equations:


## Implementation
Setting N and dt.
Fit the polynomial to the waypoints.
Calculate initial cross track error and orientation error values.
Define the components of the cost function (state, actuators, etc). You may use the methods previously discussed or make up something, up to you!
Define the model constraints. These are the state update equations defined in the Vehicle Models module.










