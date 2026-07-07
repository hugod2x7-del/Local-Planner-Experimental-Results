# Intermediate Tracking Tests

This folder contains intermediate real-world tracking experiments performed after the unit tests and before the complete Smart Retail demonstrations.

The goal of these experiments was to validate the ability of the controller to track moving targets and orientation changes in more complex real-world conditions.

## Videos

| Test | Description | Link |
|---|---|---|
| Orientation tracking 1 | Intermediate orientation tracking test with the real robotic platform. | https://youtu.be/qeAW23sDyqc |
| Orientation tracking 2 | Additional orientation tracking test with different motion conditions. | https://youtu.be/Jx_gkABp_zY |
| Smart Retail target following | Target following test in a Smart Retail-inspired setup. | https://youtu.be/BJ-ZAgrrNLk |

### Obstacle Avoidance during Target Acquisition

This test evaluates the ability of the local planner to acquire a target object while avoiding an obstacle placed near the elbow region of the robotic arm. The experiment does not correspond to the Smart Retail scenario; instead, it was designed as an intermediate validation test to evaluate the dynamic obstacle-avoidance behavior of the controller during target acquisition.

## Video

| Test | Description | Link |
|---|---|---|
| Obstacle Avoidance | Obstacle Avoidance during Target Acquisition | https://youtu.be/1a3OfqkB9y4 |

## Purpose

These experiments were used to evaluate the online adaptation capabilities of the local planner before performing full manipulation tasks involving grasping and transport.

They provide intermediate validation between isolated unit tests and the final Smart Retail experiments.
