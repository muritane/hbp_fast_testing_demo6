# iCub TR:
1. Gazebo model: should already be in NRP/Models/

2.1 URDF model: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/demonstrator6_description/urdf/icub/with_macro.urdf.xacro

2.2 TR launch file: https://github.com/HBPNeurorobotics/GazeboRosPackages/blob/demonstrator6-TR-experiments/src/target_reaching_nengo/launch/main_TR_CL_nengo_icub.launch

3. NRP experiment: https://github.com/muritane/hbp_fast_testing_demo6/tree/icub

Starting iCub TR:
1. Launch NRP experiment

    -> exception 1: Gazebo world does not load icub model, bibi_configuration file does instead
    
    -> exception 2: launch file does not start controllers, InitiCub Gazebo plugin does instead (from icub_initialization package)
    
    -> do not know why: icub model in NRP experiment is neeeded, but it is used for iCub orientation relative to world frame anyway
    
2. roslaunch target_reaching_nengo main_TR_CL_nengo_icub.launch
