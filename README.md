# Trajectory Smoothing

This repository is a wrapper around Tobias Kunz and Mike Stilman's time-optimal trajectory 
generation method from the below paper:

> Paper: Kunz, Tobias, and Mike Stilman. "Time-optimal trajectory generation for path following 
with bounded acceleration and velocity." Robotics: Science and Systems VIII (2012): 1-8.

original cpp code: https://github.com/tobiaskunz/trajectories

The code here is in turn adapted by this wrapper by Balakumar Sundaralingam:
https://github.com/balakumar-s/trajectory_smoothing
But extended with indexing of trajectory segments for allowing interpolation of orientations.

## Installing the python wrapper

1. `pip install trajectory_smoothing@git+https://github.com/colormotor/trajectory_smoothing.git`
2. Look at `examples/smooth_example.py` for an example which will draw a plot as below:

![Plot](plot.png)

