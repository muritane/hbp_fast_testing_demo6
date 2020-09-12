# KUKA visuomotor experiment:
1. Gazebo model: https://github.com/HBPNeurorobotics/demonstrator6/tree/TR-experiments/Models/kuka_iiwa_14_prismatic_gripper

2.1 URDF model: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/demonstrator6_description/urdf/iiwa_gripper.urdf.xacro

2.2 TR visuomotor experiment launch file: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/target_reaching_nengo/launch/main_TR_CL_nengo_kuka_visuomotor_experiment.launch

2.3 TR quadrat experiment launch file: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/target_reaching_nengo/launch/main_TR_CL_nengo_kuka_quadrat_experiment.launch

3. NRP experiment: https://github.com/muritane/hbp_fast_testing_demo6/tree/visuomotor_experiment

Starting KUKA visuomotor TR:
1. Launch NRP experiment
2. roslaunch target_reaching_nengo main_TR_CL_nengo_kuka_visuomotor_experiment.launch
3. rosservice call /iiwa/remove_standby_target

    -> standby target is for TCP to be near conveyer
