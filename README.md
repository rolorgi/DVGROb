# Direct Voxel Grid Robust Optimization (DVGROb)
Academic Geometry Processing project for the Deep Learning and Applied Artificial Intelligence course.

The aim of this project is to reconstruct the 3D structure of the spheroids from their flawed 2D images using Neural Networks (NN).
We start with [DVGO](https://github.com/sunset1995/DirectVoxGO.git), a NeRF-based NN modified to achieve extremely faster results, and integrate [RobustNeRF](https://robustnerf.github.io) in it to make it robust to images artifacts that are inevitabily created in the process of spheroid photography.

All scripts and dependecies are listed in the [DVGO](https://github.com/sunset1995/DirectVoxGO.git) GitHub page. I wll only upload the modified Python scripts needed to reproduce my results. In order to work, they must be replaced with the original `run.py`, `vis_volume.py` and `default.py` in the proper locations.
