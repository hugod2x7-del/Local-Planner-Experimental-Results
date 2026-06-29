# Dissertation Main Experiments

This folder contains the main real-world experiments presented in the dissertation chapter on the real robotic platform.

These experiments demonstrate the integration of the vision system, ROS communication, the Motion Manager, the local planner, and the RAMBO robotic platform.

## Videos

| Experiment | Description | Link |
|---|---|---|
| Target object tracking and acquisition | A can is manually moved in the workspace while the manipulator tracks its pose and completes the task by grasping it. | https://youtu.be/FXQe7Z5ousU |
| Object acquisition in a cluttered environment | The target object is initially placed among several objects. After manual repositioning by the operator, the robot tracks and grasps the object. | https://youtu.be/_wtJPPczem4 |
| Reacquisition, transport, and shelf placement | Complete Smart Retail-inspired task: target reacquisition, grasping, transport, and placement on a shelf. | https://youtu.be/gZVgeAUq4DI |

## Purpose

These experiments correspond to the main real-world validation results discussed in the dissertation.

They demonstrate that the proposed framework can operate on the real robotic platform and execute manipulation tasks relevant to the Smart Retail context.

## Observed Limitations

The experiments also highlight practical limitations of real-world execution, including:

- measurement noise;
- communication latency;
- visual tracking limitations;
- occlusions caused by clutter or by the gripper;
- dependence on controller tuning;
- limited tracking of multiple objects.

Despite these limitations, the experiments confirm the feasibility of integrating perception, planning, and control on the RAMBO platform.
