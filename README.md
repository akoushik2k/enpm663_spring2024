# enpm663_spring2024

## Lecture 9: Motion Planning with MoveIt!

- alias start_ariac='ros2 launch ariac_gazebo ariac.launch.py competitor_pkg:=moveit_demo'
- alias start_moveit='ros2 launch ariac_moveit_config ariac_robots_moveit.launch.py'
- alias start_competition='ros2 service call /ariac/start_competition std_srvs/srv/Trigger'
- alias start_rqt_joint='ros2 run rqt_joint_trajectory_controller rqt_joint_trajectory_controller --force-discover'
- alias start_cpp_demo='ros2 launch moveit_demo demo_cpp.launch.py rviz:=true'
- alias start_cpp_python_demo='ros2 launch moveit_demo demo_cpp_python.launch.py'

## To run only C++ demo
start_ariac
start_moveit
start_cpp_demo

## To run only Python/C++ demo
start_ariac
start_moveit
start_cpp_python_demo