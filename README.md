# Modelling-and-Control-of-Mobile-Robot-Formations

This is a Technical Paper report of "Modeling and Control of Formations of Nonholonomic Mobile Robots" by Jaydev P. Desai, James P. Ostrowski, and Vijay Kumar.

This paper addresses the control of a team of nonholonomic mobile robots navigating with obstacles while maintaining a desired formation and changing formations when required, using nonlinear control theory and graph theory. We use the terms l−ψ and l − l, which are based on tracking the position and orientation of the robot relative to the leader, or the position of two leaders. Defining the concept of a transition matrix, we present an exhaustive list of all possible that can occur in the robot formation and the corresponding transition matrix column.

![image](https://github.com/AbhinavB7/Modelling-and-Control-of-Robot-Formations/assets/87815926/ef1e39a1-ebe5-4667-9e2a-61a38644a44a)

There are different laws according to the type of control the robot has 
<p float="left">
  <img src="https://github.com/AbhinavB7/Modelling-and-Control-of-Robot-Formations/assets/87815926/4ef3c36a-479c-4ba5-b0c2-dcdafbcd7185" width="500" />
  <img src="https://github.com/AbhinavB7/Modelling-and-Control-of-Robot-Formations/assets/87815926/408caa12-7bd0-4d17-b5b7-85bf67ea689a" width="500" /> 
</p>    

We read about the enumerations and transitions in the formations of the robots. We define **Control Graph** for different constraints that can occur. Some of the examples are given below showing the transition laws we should follow.

![image](https://github.com/AbhinavB7/Modelling-and-Control-of-Robot-Formations/assets/87815926/fa66ace1-5f2f-4a82-a3d4-8819173c3260)

We then simulate the two examples in MATLAB and get the following results.

<p float="left">
  <img src="https://github.com/AbhinavB7/Modelling-and-Control-of-Robot-Formations/assets/87815926/80ed706c-8d5c-4e79-8881-082cc6b358a3" width="500" />
  <img src="https://github.com/AbhinavB7/Modelling-and-Control-of-Robot-Formations/assets/87815926/fbd62c01-1d43-4afc-8fe9-3d0679e85d83" width="500" /> 
</p>    
