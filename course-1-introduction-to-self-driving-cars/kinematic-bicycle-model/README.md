In this assignment, I have implement the kinematic bicycle model. The model accepts velocity and steering rate inputs and steps through the bicycle kinematic equations. 
Once the model is implemented, a set of inputs was provided to drive the bicycle in a figure eight (8) trajectory.

The bicycle kinematics are governed by the following set of equations:




 
 
 
where the inputs are the bicycle speed  and steering angle rate . The input can also directly be the steering angle  rather than its rate in the simplified case. 

In order to create this model, Python class objects was used to allows to store the state variables as well as make functions for implementing the bicycle kinematics.

The bicycle begins with zero initial conditions, has a maximum turning rate of 1.22 rad/s, a wheelbase length of 2m, and a length of 1.2m to its center of mass from 
the rear axle.
