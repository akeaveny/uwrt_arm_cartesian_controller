# uwrt_arm_cartesian_controller

Here's the underlying algorithm for Cartesian Control.
KDL's IK solver can be found [here](http://docs.ros.org/jade/api/orocos_kdl/html/classKDL_1_1ChainIkSolverVel.html#a761853db487c901485737c6334953cbe) which use's Denavit–Hartenberg parameter's refer to [Modern Robitocs - Appendix C](http://hades.mech.northwestern.edu/images/7/7f/MR.pdf)
![image](https://user-images.githubusercontent.com/56097508/87878649-9dae5b80-c9b3-11ea-87d1-782b8f4b7fae.png)

Check out our 2021 SAR submission for this year's (cancelled) URC competition [here](https://www.youtube.com/watch?v=b9UxN_oN-Sw).

Here is a sample of our us controlling our robot arm with IK in sim (we send commands with our xbox controller)!
![Alt text](samples/demo.gif?raw=true "Title")
