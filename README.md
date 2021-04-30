# UR_ROS_Gazebo simulation

Most tutorials on control manipulators that I found adopt MoveIt, which is a nice software pack for ROS. But MoveIt encapsulates its algorithm, such as kinematics and planning, in a highly abstracted level.
I am trying to implement those algorithms myself, and the only interface to control the manipulator is a 1x6 joint vector.
