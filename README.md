# Multi-robot experiment:
1. Gazebo model: https://github.com/HBPNeurorobotics/demonstrator6/tree/TR-experiments/Models/iiwa_panda_lwa4p_ur5e

2.1 URDF model: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/demonstrator6_description/urdf/multiple_robots/multiple_robots.urdf.xacro

2.2 TR launch file: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/target_reaching_nengo/launch/main_TR_CL_nengo_multi_robot_experiment.launch

3. NRP experiment: https://github.com/muritane/hbp_fast_testing_demo6/tree/multi_robot_experiment

Starting multi-robot TR:
1. Launch NRP experiment
2. Go to NRP experiment directory
3. roslaunch multiple_robots_part_2_separate.launch

    -> timeout if starting both parts together
4. roslaunch target_reaching_nengo main_TR_CL_nengo_multi_robot_experiment.launch

    -> can be launched separately
