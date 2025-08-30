Geometric-Transformations-with-Image-Processing

This repository provides simple yet illustrative Python + Matplotlib demos of fundamental geometric transformations frequently applied in image processing and computer vision.
The implementations are inspired by the formulations in Computer Vision: Algorithms and Applications (Szeliski, 2010/2018 edition).


📌 Transformations Included

1. Euclidean Transformations

Combines: Rotation + Translation

Maintains shape and size (rigid body motion).

Defined using a rotation matrix plus a translation vector.

Example: A square rotated and repositioned.


2. Similarity Transformations

Combines: Rotation + Translation + Uniform Scaling

Preserves shape, but alters overall scale.

Special instance of affine transformations with scaling factor k.

Example: A square rotated, moved, and resized uniformly.


3. Affine Transformations

Combines: Rotation, Translation, Scaling (uniform/non-uniform), Shearing

Preserves parallelism of lines, but not exact angles or distances.

Represented by a 2×3 affine transformation matrix.

Example: A square reshaped into a rectangle or a slanted parallelogram.


4. Projective Transformations (Homography)

Most general 2D linear transformation.

Combines: Translation, Rotation, Scaling, Shear, and Perspective distortion

Ensures straight lines remain straight, but parallel lines may converge (vanishing point).

Represented by a 3×3 homography matrix in homogeneous coordinates.

Example: A square transformed into a trapezoid (mimicking perspective view).


📂 Repository Structure

euclidean_transform.py – Rotation + Translation

similarity_transform.py – Rotation + Translation + Uniform Scaling

affine_transform.py – General affine transformations (non-uniform scaling, shear)

projective_transform.py – Homography with perspective effects
