# 3D-Gaussian-Splatting
## Overview
This is a Colab notebook applying a part of https://github.com/graphdeco-inria/gaussian-splatting method. Only made to train a first model with minimal requierment, be able to create a PLY file in order to visualize it later in Spline or Super Splat.

## Pre-requierments
Record a video of the scene to process (many angles, point of view). Use FFMPEG to extract 1-2 frames per second of that video.

## Notebook
- First, connect to GPU (T4) environment.
- Upload your frames extracted from you recording to a folder named "input".
- Run the whole notebook.
- Trained model can find under /content/trained.
- Download "point_cloud", this is the Gaussian Splatting 3D model PLY file.
