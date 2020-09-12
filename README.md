# LWA4P quadrat experiment:
1. Gazebo model: https://github.com/HBPNeurorobotics/demonstrator6/tree/TR-experiments/Models/schunk_lwa4p_with_svh_hand

2.1 URDF model: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/demonstrator6_description/urdf/lwa4p/lwa4p_with_hand.urdf.xacro

2.2 TR quadrat experiment launch file: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/target_reaching_nengo/launch/main_TR_CL_nengo_lwa4p_quadrat_experiment.launch

3. NRP experiment: https://github.com/muritane/hbp_fast_testing_demo6/tree/lwa4p_quadrat_experiment

Starting KUKA TR:
1. Launch NRP experiment
2. roslaunch target_reaching_nengo main_TR_CL_nengo_lwa4p_quadrat_experiment.launch
