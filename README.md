# Awesome-Algorithms-Against-Degeneracy

This repository contains a curated list of resources addressing degeneracy, particularly geometric degeneracy that leads to LiDAR-slip. Below is an example illustrating a robot traversing a tunnel with self-similar environmental features.

![1641833866_1](README.assets/1641833866_1.gif)

**Please feel free to send me [pull requests](https://github.com/thisparticle/Awesome-Implicit-NeRF-Robotics/blob/main/how-to-PR.md) or [email](mailto:muhammadzubairirshad@gmail.com) to add papers!**

If you find this repository useful, please consider STARing this list. Feel free to share this list with others!

---
## Table of contents

[TOC]

<details span>
<summary><b>Update Log:</b></summary>
<br>
**Oct 19, 2024**
- Added 5 papers: Kinematic-ICP, Switch-slam, DRPM, A Point-to-distribution Degeneracy Detection Factor for LiDAR SLAM using Local Geometric Models, Informed, Constrained, Aligned: A Field Analysis on Degeneracy-aware Point Cloud Registration in the Wild

**July 17, 2024**

- create repo

</details>
<br> 

---
## Degeneracy  detection and mitigation 

* Informed, Constrained, Aligned: A Field Analysis on Degeneracy-aware Point Cloud Registration in the Wild, arXiv, 2024. [[paper](https://arxiv.org/abs/2408.11809)]
* DRPM: Degeneracy Resilient Point-to-Plane Error Minimization, RAL, 2024. [[paper](https://arxiv.org/abs/2410.10784)] [[code](https://github.com/ntnu-arl/drpm?tab=readme-ov-file)]
* A Point-to-distribution Degeneracy Detection Factor for LiDAR SLAM using Local Geometric Models, ICRA, 2024. [[paper](https://ieeexplore.ieee.org/document/10610340/)] [[code](https://github.com/jisehua/Degenerate-Detection)]
* X-ICP: Localizability-Aware LiDAR Registration for Robust Localization in Extreme Environments, TRO, 2024. [[Paper](https://ieeexplore.ieee.org/document/10328716)] [[Webpage](https://sites.google.com/leggedrobotics.com/x-icp)] 
* Learning-based Localizability Estimation for Robust LiDAR Localization, IROS, 2022. [[paper](https://ieeexplore.ieee.org/document/9982257)] [[code](https://github.com/leggedrobotics/L3E)]
* Robust Rank Deficient SLAM, IROS, 2021. [[paper](https://ieeexplore.ieee.org/document/9636443)]
* Degeneracy-Aware Factors with Applications to Underwater SLAM, IROS, 2019. [[paper](https://ieeexplore.ieee.org/document/8968577/)]
* Estimating the Localizability in Tunnel-like Environments using LiDAR and UWB, ICRA, 2019. [[paper](https://ieeexplore.ieee.org/document/8794167)]
* Predicting Alignment Risk to Prevent Localization Failure, ICRA, 2018. [[paper](https://ieeexplore.ieee.org/document/8462890)]
* On degeneracy of optimization-based state estimation problems, ICRA, 2016. [[paper](https://ieeexplore.ieee.org/document/7487211)]

---
## Robust SLAM

* Switch-slam: Switching-based lidar-inertial-visual slam for degenerate environments, RAL, 2024. [[paper](https://ieeexplore.ieee.org/document/10582434)]

* Kinematic-ICP: Enhancing LiDAR Odometry with Kinematic Constraints for Wheeled Mobile Robots Moving on Planar Surfaces, arXiv, 2024. [[paper](https://arxiv.org/abs/2410.10277)]

* FAST-LIVO2: Fast, Direct LiDAR-Inertial-Visual Odometry, TRO, 2024. [[paper](https://ieeexplore.ieee.org/document/9739244)] [[code](https://github.com/hku-mars/FAST-LIVO2)]
* Four years of multimodal odometry and mapping on the rail vehicles, JFR, 2024. [[paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22256)]
* LIVER: A Tightly Coupled LiDAR-Inertial-Visual State Estimator With High Robustness for Underground Environments, RAL, 2024. [[paper](https://ieeexplore.ieee.org/document/10404014)]

* COIN-LIO: Complementary Intensity-Augmented LiDAR Inertial Odometry, ICRA, 2024. [[arXiv](https://arxiv.org/abs/2310.01235)] [[code](https://github.com/ethz-asl/COIN-LIO)]
* Degradation Resilient LiDAR-Radar-Inertial Odometry, ICRA, 2024. [[arXiv](https://arxiv.org/abs/2403.05332)]
* RELEAD: Resilient Localization with Enhanced LiDAR Odometry in Adverse Environments, ICRA, 2024. [[arXiv](https://arxiv.org/abs/2402.18934)]
* R3LIVE: A Robust, Real-time, RGB-colored, LiDAR-Inertial-Visual tightly-coupled state Estimation and mapping package, ICRA,2022. [[paper](https://ieeexplore.ieee.org/document/9811935)] [[code](https://github.com/hku-mars/r3live)]
* Super odometry: Imu-centric lidar-visual-inertial estimator for challenging environments, IROS, 2021. [[paper](https://arxiv.org/pdf/2104.14938)]
* LVI-SAM: Tightly-coupled Lidar-Visual-Inertial Odometry via Smoothing and Mapping, ICRA, 2021. [[paper](https://github.com/TixiaoShan/LVI-SAM/blob/master/doc/paper.pdf)] [[code](https://github.com/TixiaoShan/LVI-SAM)]
* Complementary Multi–Modal Sensor Fusion for Resilient Robot Pose Estimation in Subterranean Environments, ICUAS, 2020. [[paper](https://ieeexplore.ieee.org/document/9213865)]

## Point Cloud Registration

* RMS: Redundancy-Minimizing Point Cloud Sampling for Real-Time Pose Estimation, RAL, 2024. [[paper](https://ieeexplore.ieee.org/document/10502131)] [[code](https://github.com/ctu-mrs/RMS)]
* Toward Certifying Maps for Safe Registration-Based Localization Under Adverse Conditions, RAL, 2023. [[paper](https://arxiv.org/abs/2309.04251)]

---
## Dataset

* GEODE dataset: Heterogeneous LiDAR Dataset for Benchmarking Robust Localization in Diverse Degenerate Scenarios, arXiv, 2024. [[Paper](https://arxiv.org/abs/2409.04961)] [[website](https://thisparticle.github.io/geode/)]
* SubT-MRS: Pushing SLAM Towards All-weather Environments, CVPR, 2024. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhao_SubT-MRS_Dataset_Pushing_SLAM_Towards_All-weather_Environments_CVPR_2024_paper.pdf)] [[website](https://superodometry.com/datasets)]
* [ENWIDE Dataset](https://projects.asl.ethz.ch/datasets/enwide) (related paper: COIN-LIO: Complementary Intensity-Augmented LiDAR Inertial Odometry, ICRA, 2024. [[arXiv](https://arxiv.org/abs/2310.01235)] [[code](https://github.com/ethz-asl/COIN-LIO)])
* [LiDAR Degeneracy Datasets](https://github.com/ntnu-arl/lidar_degeneracy_datasets) (related paper: Degradation Resilient LiDAR-Radar-Inertial Odometry, ICRA, 2024. [[arXiv](https://arxiv.org/abs/2403.05332)])
* WHU-Helmet: A helmet-based multi-sensor SLAM dataset for the evaluation of real-time 3D mapping in large-scale GNSS-denied environments, IEEE Transactions on Geoscience and Remote Sensing, 2023. [[paper](https://ieeexplore.ieee.org/document/10123040/)] [[website](https://github.com/kafeiyin00/WHU-HelmetDataset)]
* [Railroad-dataset](https://github.com/YushengWHU/Railroad-dataset)
* Open-source datasets released by the SubT teams
  * [CERBERUS](https://www.subt-cerberus.org/code--data.html)
  * [CoSTAR](https://github.com/NeBula-Autonomy)
  * [CTU-CRAS-Norlab](https://github.com/ctu-mrs/slam_datasets)
  * [Explorer](https://theairlab.org/dataset/interestingness)
  * [MARBLE  COLORADAR DATASET](https://arpg.github.io/coloradar/)

----
