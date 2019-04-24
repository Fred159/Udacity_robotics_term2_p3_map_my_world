# Udacity_robotics_term2_p3_map_my_world
#### Kitchen dining world slam video link: https://youtu.be/qYA9j-TyDLs
#### Ming world slam video link : https://www.youtube.com/watch?v=zzsqAUZuVFk
### Abstract
SLAM is a key problem in robotics. Because of the infinite states and variables, SLAM is a difficult problem. What is more,
environment can be dynamic. Once the environment turn in to dynamic, time is also should be considered into algorithm. GraphSLAM
is a one of the powerful solutions. It makes a sparse matrix for mapping features and states. The sparse matrix is used for construct
constraints for each connections. The reason why use sparse is that system can’t save and do not have to save all the connections
relationship. It just keep the important weight about the connections which is directly connected. Actually, the connections are
formulated into Gaussian distribution. GraphSLAM has the capability for handling full SLAM problem with the constraints sparse
matrix’s help. The simulation system is constructed based on gazebo and rviz.
Index Terms—Robot, ROS, Udacity, LATEX, Localization, GraphSLAM, AMCL.

![user defined world simulation with rtab-map](https://github.com/Fred159/Udacity_robotics_term2_p3_map_my_world/blob/master/ros%20rtab.png)
