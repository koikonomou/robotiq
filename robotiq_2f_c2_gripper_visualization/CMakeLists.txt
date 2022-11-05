cmake_minimum_required(VERSION 3.0.2)
project(robotiq_2f_c2_gripper_visualization)


find_package(catkin REQUIRED COMPONENTS
  controller_manager
  effort_controllers
  gazebo_ros
  gazebo_ros_control
  joint_state_controller
  joint_trajectory_controller
  robot_state_publisher
  moveit_kinematics
)
catkin_package()
include_directories(
  ${catkin_INCLUDE_DIRS}
)
# install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
# install(DIRECTORY meshes DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
