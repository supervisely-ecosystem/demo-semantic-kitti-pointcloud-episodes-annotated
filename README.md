<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250" /> <br>

# SemanticKITTI Point Cloud Episodes Annotated

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#use-cases">Use Cases</a> •
  <a href="#license-and-citation">License and Citation</a> •
  <a href="#download">Download</a>
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/demo-semantic-kitti-pointcloud-episodes-annotated)
[![views](https://app.supervisely.com/img/badges/views/supervisely-ecosystem/demo-semantic-kitti-pointcloud-episodes-annotated.png)](https://supervisely.com)
[![downloads](https://app.supervisely.com/img/badges/downloads/supervisely-ecosystem/demo-semantic-kitti-pointcloud-episodes-annotated.png)](https://supervisely.com)

</div>

## Overview

This is an annotated sample project featuring SemanticKITTI point cloud episodes with semantic segmentation of urban driving scenes. The dataset includes 3D LiDAR scans captured from autonomous vehicles navigating city streets, with pre-annotated semantic labels for cars, roads, buildings, vegetation, and other urban elements.

**Data Source:** This sample is based on the [SemanticKITTI dataset](https://semantic-kitti.org/), which provides sequential point cloud frames organized as episodes, making it ideal for developing and testing 3D perception algorithms for autonomous driving applications.

<img src="https://github.com/supervisely-ecosystem/demo-semantic-kitti-pointcloud-episodes-annotated/releases/download/v1.0.0/semantickitti-preview.png" />

## Use Cases

This type of annotated point cloud data is essential for autonomous driving and robotics applications. Development teams can use similar labeled data to:

- **3D Object Detection** — train models to detect and localize vehicles, pedestrians, and cyclists in 3D space for safe navigation
- **Semantic Segmentation** — segment road surfaces, sidewalks, buildings, and vegetation for scene understanding
- **Scene Understanding** — build comprehensive 3D maps of urban environments with semantic information
- **Motion Planning** — use annotated episodes to develop and test trajectory planning algorithms
- **Sensor Fusion** — combine LiDAR point clouds with camera data for robust perception systems
- **Simulation and Testing** — validate perception algorithms on real-world annotated data before deployment

In the [SemanticKITTI format documentation](https://docs.supervisely.com/import-and-export/import/supported-annotation-formats/pointcloud_episodes/semantickitti), you can find detailed information about dataset structure, supported formats, import/export options, and best practices for working with SemanticKITTI data in Supervisely.

## License and Citation

This sample is based on the [SemanticKITTI dataset](https://semantic-kitti.org/), which is distributed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

**Important:** The data is free to share and adapt, but **cannot be used for commercial purposes**. You must give appropriate credit by citing the original work.

If you use this data or dataset, please cite the following papers:

**SemanticKITTI:**

```bibtex
@inproceedings{behley2019iccv,
  author = {J. Behley and M. Garbade and A. Milioto and J. Quenzel and S. Behnke and C. Stachniss and J. Gall},
  title = {{SemanticKITTI: A Dataset for Semantic Scene Understanding of LiDAR Sequences}},
  booktitle = {Proc. of the IEEE/CVF International Conf.~on Computer Vision (ICCV)},
  year = {2019}
}
```

**Original KITTI Vision Benchmark:**

```bibtex
@inproceedings{geiger2012cvpr,
  author = {A. Geiger and P. Lenz and R. Urtasun},
  title = {{Are we ready for Autonomous Driving? The KITTI Vision Benchmark Suite}},
  booktitle = {Proc.~of the IEEE Conf.~on Computer Vision and Pattern Recognition (CVPR)},
  pages = {3354--3361},
  year = {2012}
}
```

## Download

Download sample dataset in SemanticKITTI format (15 MB): [Download ZIP archive](https://github.com/supervisely-ecosystem/demo-semantic-kitti-pointcloud-episodes-annotated/releases/download/v1.0.0/project-example.zip)
