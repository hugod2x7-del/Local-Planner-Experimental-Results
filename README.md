# Local Planner Experimental Results

This repository contains supplementary real-world experimental results obtained with the local planner implemented on the RAMBO robotic platform.

The material presented here accompanies the dissertation:

**Motion Planning and Control for an Anthropomorphic Robot Involved in Human-Robot Interaction**

The videos document the progressive validation of the proposed framework, starting from unitary tracking tests and moving towards increasingly complex Smart Retail manipulation scenarios.

## Repository Organization

| Folder | Description |
|---|---|
| `01_unit_tests` | Individual validation tests for roll, pitch, yaw, and orientation tracking. |
| `02_intermediate_tracking_tests` | Intermediate target and orientation tracking experiments. |
| `03_smart_retail_scenarios` | Smart Retail inspired experiments, including target following, picking, and transport. |
| `04_dissertation_main_experiments` | Main real-world experiments presented in the dissertation. |

## Experimental Context

The experiments were performed using the RAMBO robotic platform, integrating:

- the real robotic manipulators;
- the ROS communication architecture;
- the Motion Manager;
- the local planner;
- the vision system;
- the OnRobot gripper.

The goal of these experiments is to demonstrate the feasibility of integrating perception, planning, and control in real-world manipulation tasks.

## Notes

Some of the experiments require human intervention to reposition the target object, especially in cluttered scenarios where the object is initially difficult to reach. These interactions are representative of human-robot collaboration situations in partially structured environments.

The repository may be updated with additional experimental videos and supplementary validation results.

## License

Unless otherwise stated, the material in this repository is provided as supplementary material for academic and research purposes. Please cite the associated dissertation when using or referencing these results.
