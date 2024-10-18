# 3D Point Cloud Generation from Photographs

This project focuses on creating a 3D point cloud from a series of photographs taken from a mobile device. By leveraging camera calibration and structure-from-motion (SfM) techniques, we aim to reconstruct a detailed three-dimensional representation of a scene captured in multiple frames.

## Key Techniques Used

1. **Chessboard Calibration**:  
   Utilized chessboard calibration to compute the camera matrix, ensuring accurate mapping between 2D image coordinates and 3D world points.

2. **Structure from Motion (SfM)**:  
   Applied the SfM technique to analyze consecutive scene frames and generate dense point clouds. This process involves feature detection, matching, and triangulation to reconstruct the spatial arrangement of points.

## Project Structure

- '3d_points_code.ipynb': Contains the code for camera calibration and 3d point cloud generation.
- 'calibration_images/': Directory that contains the calibration images used.
- 'test_data/': Directory for input images
- 'output/': Folder to store generated point clouds.
