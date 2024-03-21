# ros-build-farm-statuses

MRPT (and related libs) ROS build farm dashboard

<!-- toc -->

- [mrpt2](#mrpt2)
- [nanoflann](#nanoflann)
- [mvsim](#mvsim)
- [mrpt_path_planning](#mrpt_path_planning)
- [mp2p_icp](#mp2p_icp)
- [mola_test_datasets](#mola_test_datasets)
- [mrpt_navigation](#mrpt_navigation)
- [mrpt_msgs](#mrpt_msgs)
- [mrpt_slam](#mrpt_slam)
- [pose_cov_ops](#pose_cov_ops)
- [mrpt_sensors](#mrpt_sensors)
- [mola_common](#mola_common-1)
- [MOLA](#mola)
  * [MOLA binary packages](#mola-binary-packages)
- [gtsam](#gtsam)

<!-- tocstop -->

### mrpt2
- Sources: https://github.com/MRPT/mrpt/
- Documentation: https://docs.mrpt.org/reference/latest/

| Distro | `develop` branch  | Next builds | Stable release |
|---|---|---|---|
| ROS1 Noetic @ u20.04 | [![Build Status](https://build.ros.org/job/Ndev__mrpt2__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__mrpt2__ubuntu_focal_amd64/) |  [![Build Status](https://build.ros.org/job/Nbin_uF64__mrpt2__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mrpt2__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/mrpt2)](https://index.ros.org/search/?term=mrpt2) |
| ROS2 Humble @ u22.04 | [![Build Status](https://build.ros2.org/job/Hdev__mrpt2__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mrpt2__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mrpt2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mrpt2__ubuntu_jammy_amd64__binary/) |  [![Version](https://img.shields.io/ros/v/humble/mrpt2)](https://index.ros.org/search/?term=mrpt2) | 
| ROS2 Iron @ u22.04 | [![Build Status](https://build.ros2.org/job/Idev__mrpt2__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mrpt2__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mrpt2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mrpt2__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/iron/mrpt2)](https://index.ros.org/search/?term=mrpt2) | 
| ROS2 Rolling @ u24.04 | [![Build Status](https://build.ros2.org/job/Rdev__mrpt2__ubuntu_noble_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mrpt2__ubuntu_noble_amd64/) | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mrpt2__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mrpt2__ubuntu_noble_amd64__binary/) | [![Version](https://img.shields.io/ros/v/rolling/mrpt2)](https://index.ros.org/search/?term=mrpt2) |

### nanoflann 

Sources: https://github.com/jlblancoc/nanoflann

Shipped as:
- Debian package: https://tracker.debian.org/pkg/nanoflann
- Ubuntu package: https://launchpad.net/ubuntu/+source/nanoflann


### mvsim

Sources: https://github.com/MRPT/mvsim

| Distro | Build dev | Build releases | Stable version |
| ---    | ---       | ---            | ---         |
| ROS 1 Noetic (u20.04) | [![Build Status](https://build.ros.org/job/Ndev__mvsim__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__mvsim__ubuntu_focal_amd64/) |  [![Build Status](https://build.ros.org/job/Nbin_uF64__mvsim__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mvsim__ubuntu_focal_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/noetic/mvsim)](https://index.ros.org/search/?term=mvsim) |
| ROS 2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mvsim__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mvsim__ubuntu_jammy_amd64/) |  [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mvsim__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mvsim__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/humble/mvsim)](https://index.ros.org/search/?term=mvsim) |
| ROS 2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mvsim__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mvsim__ubuntu_jammy_amd64/) |  [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mvsim__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mvsim__ubuntu_jammy_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/iron/mvsim)](https://index.ros.org/search/?term=mvsim) |
| ROS 2 Rolling (u24.04) | [![Build Status](https://build.ros2.org/job/Rdev__mvsim__ubuntu_noble_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mvsim__ubuntu_noble_amd64/) |  [![Build Status](https://build.ros2.org/job/Rbin_uN64__mvsim__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mvsim__ubuntu_noble_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/rolling/mvsim)](https://index.ros.org/search/?term=mvsim) |


### mrpt_path_planning
[Source](https://github.com/MRPT/mrpt_path_planning), [ROS 1 release repo](https://github.com/mrpt-ros-pkg-release/mrpt_path_planning-release), [ROS 2 release repo](https://github.com/ros2-gbp/mrpt_path_planning-release)

| Distro | Build dev | Build releases | Stable version |
| ---    | ---       | ---            | ---         |
| ROS 1 Noetic (u20.04) | [![Build Status](https://build.ros.org/job/Ndev__mrpt_path_planning__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__mrpt_path_planning__ubuntu_focal_amd64/) | [![Build Status](https://build.ros.org/job/Nbin_uF64__mrpt_path_planning__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mrpt_path_planning__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/mrpt_path_planning)](https://index.ros.org/search/?term=mrpt_path_planning) |
| ROS 2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mrpt_path_planning__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mrpt_path_planning__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mrpt_path_planning__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mrpt_path_planning__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/humble/mrpt_path_planning)](https://index.ros.org/search/?term=mrpt_path_planning) |
| ROS 2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mrpt_path_planning__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mrpt_path_planning__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mrpt_path_planning__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mrpt_path_planning__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/iron/mrpt_path_planning)](https://index.ros.org/search/?term=mrpt_path_planning) |
| ROS 2 Rolling (u22.04) | [![Build Status](https://build.ros2.org/job/Rdev__mrpt_path_planning__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mrpt_path_planning__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mrpt_path_planning__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mrpt_path_planning__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/rolling/mrpt_path_planning)](https://index.ros.org/search/?term=mrpt_path_planning) |

### mp2p_icp

Sources: https://github.com/MOLAorg/mp2p_icp

| Distro | Build dev | Build releases | Stable version |
| ---    | ---       | ---            | ---         |
| ROS 2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mp2p_icp__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mp2p_icp__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mp2p_icp__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mp2p_icp__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/humble/mp2p_icp)](https://index.ros.org/search/?term=mp2p_icp) |
| ROS 2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mp2p_icp__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mp2p_icp__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mp2p_icp__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mp2p_icp__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/iron/mp2p_icp)](https://index.ros.org/search/?term=mp2p_icp) |
| ROS 2 Rolling (u22.04) | [![Build Status](https://build.ros2.org/job/Rdev__mp2p_icp__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mp2p_icp__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Rbin_uJ64__mp2p_icp__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uJ64__mp2p_icp__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/rolling/mp2p_icp)](https://index.ros.org/search/?term=mp2p_icp) |

| Deprecated distros | Build releases | Stable version |
| ---                |  ---           | ---            |
| ROS 1 Noetic (u20.04) | [![Build Status](https://build.ros.org/job/Nbin_uF64__mp2p_icp__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mp2p_icp__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/mp2p_icp)](https://index.ros.org/search/?term=mp2p_icp) |


### mola_test_datasets

| Distro | Build dev | Build releases | Stable version |
| ---    | ---       | ---            | ---         |
| ROS 2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mola_test_datasets__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mola_test_datasets__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_test_datasets__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_test_datasets__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/humble/mola_test_datasets)](https://index.ros.org/search/?term=mola_test_datasets) |
| ROS 2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mola_test_datasets__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mola_test_datasets__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_test_datasets__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_test_datasets__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/iron/mola_test_datasets)](https://index.ros.org/search/?term=mola_test_datasets) |
| ROS 2 Rolling (u22.04) | [![Build Status](https://build.ros2.org/job/Rdev__mola_test_datasets__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mola_test_datasets__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Rbin_uJ64__mola_test_datasets__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uJ64__mola_test_datasets__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/rolling/mola_test_datasets)](https://index.ros.org/search/?term=mola_test_datasets) |


### mrpt_navigation

- Sources: https://github.com/mrpt-ros-pkg/mrpt_navigation
- ROS wiki: https://wiki.ros.org/mrpt_navigation

| Distro | Build dev | Build release | Stable sync |
| --- | --- | --- | --- |
| ROS1 Noetic (u20.04) | [![Build Status](https://build.ros.org/job/Ndev__mrpt_navigation__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__mrpt_navigation__ubuntu_focal_amd64/) |  [![Build Status](https://build.ros.org/job/Nbin_uF64__mrpt_navigation__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mrpt_navigation__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/mrpt_navigation)](https://index.ros.org/search/?term=mrpt_navigation) |
| ROS 2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mrpt_navigation__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mrpt_navigation__ubuntu_jammy_amd64/) |  TBD | [![Version](https://img.shields.io/ros/v/iron/mrpt_navigation)](https://index.ros.org/search/?term=mrpt_navigation) |
| ROS 2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mrpt_navigation__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mrpt_navigation__ubuntu_jammy_amd64/) |  TBD | [![Version](https://img.shields.io/ros/v/iron/mrpt_navigation)](https://index.ros.org/search/?term=mrpt_navigation) |
| ROS 2 Rolling (u22.04) | [![Build Status](https://build.ros2.org/job/Rdev__mrpt_navigation__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mrpt_navigation__ubuntu_jammy_amd64/) |  TBD | [![Version](https://img.shields.io/ros/v/rolling/mrpt_navigation)](https://index.ros.org/search/?term=mrpt_navigation) |

### mrpt_msgs

Sources: https://github.com/mrpt-ros-pkg/mrpt_msgs

| Distro | Develop branch | Build next | Stable release |
| --- | --- | --- | --- |
| ROS1 Noetic (u20.04) | [![Build Status](https://build.ros.org/job/Ndev__mrpt_msgs__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__mrpt_msgs__ubuntu_focal_amd64/) | [![Build Status](https://build.ros.org/job/Nbin_uF64__mrpt_msgs__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mrpt_msgs__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/mrpt_msgs)](https://index.ros.org/search/?term=mrpt_msgs) |
| ROS2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mrpt_msgs__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mrpt_msgs__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mrpt_msgs__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mrpt_msgs__ubuntu_jammy_arm64__binary/) | [![Version](https://img.shields.io/ros/v/humble/mrpt_msgs)](https://index.ros.org/search/?term=mrpt_msgs) |
| ROS2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mrpt_msgs__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mrpt_msgs__ubuntu_jammy_amd64/) |  [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mrpt_msgs__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mrpt_msgs__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/iron/mrpt_msgs)](https://index.ros.org/search/?term=mrpt_msgs) |
| ROS2 Rolling (u22.04) | [![Build Status](https://build.ros2.org/job/Rdev__mrpt_msgs__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mrpt_msgs__ubuntu_jammy_amd64/) |  [![Build Status](https://build.ros2.org/job/Rbin_uJ64__mrpt_msgs__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uJ64__mrpt_msgs__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/rolling/mrpt_msgs)](https://index.ros.org/search/?term=mrpt_msgs) |

### mrpt_slam

Sources: https://github.com/mrpt-ros-pkg/mrpt_slam

| Distro | Build dev | Build release | Stable release |
| --- | --- | --- | --- |
|  ROS1 Noetic @ u20.04 | [![Build Status](https://build.ros.org/job/Ndev__mrpt_slam__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__mrpt_slam__ubuntu_focal_amd64/) | [![Build Status](https://build.ros.org/job/Nbin_uF64__mrpt_slam__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mrpt_slam__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/mrpt_slam)](https://index.ros.org/search/?term=mrpt_slam) |

Non-maintained for ROS 2 (volunteers? ;-).

### pose_cov_ops

Sources: https://github.com/mrpt-ros-pkg/pose_cov_ops

| Distro | Develop branch | Releases | Stable release |
| ---    | ---            | ---      |  ---      |
| ROS1 Noetic (u20.04) | [![Build Status](https://build.ros.org/job/Ndev__pose_cov_ops__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__pose_cov_ops__ubuntu_focal_amd64/) | [![Build Status](https://build.ros.org/job/Nbin_uF64__pose_cov_ops__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__pose_cov_ops__ubuntu_focal_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/noetic/pose_cov_ops)](https://index.ros.org/search/?term=pose_cov_ops) |
| ROS2 Humble  (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__pose_cov_ops__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__pose_cov_ops__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__pose_cov_ops__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__pose_cov_ops__ubuntu_jammy_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/humble/pose_cov_ops)](https://index.ros.org/search/?term=pose_cov_ops) |
| ROS2 Iron  (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__pose_cov_ops__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__pose_cov_ops__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__pose_cov_ops__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__pose_cov_ops__ubuntu_jammy_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/iron/pose_cov_ops)](https://index.ros.org/search/?term=pose_cov_ops) |
| ROS2 Rolling (u22.04) | [![Build Status](https://build.ros2.org/job/Rdev__pose_cov_ops__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__pose_cov_ops__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Rbin_uJ64__pose_cov_ops__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uJ64__pose_cov_ops__ubuntu_jammy_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/rolling/pose_cov_ops)](https://index.ros.org/search/?term=pose_cov_ops) |


### mrpt_sensors

[Sources](https://github.com/mrpt-ros-pkg/mrpt_sensors/)

| Distro | Build dev | Build release | Stable release |
| --- | --- | --- | --- |
| ROS2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mrpt_sensors__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mrpt_sensors__ubuntu_jammy_amd64/) |  xxx | xxx |
| ROS2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mrpt_sensors__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mrpt_sensors__ubuntu_jammy_amd64/) |  xxx | xxx |
| ROS2 Rolling (u24.04) | [![Build Status](https://build.ros2.org/job/Rdev__mrpt_sensors__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mrpt_sensors__ubuntu_jammy_amd64/) |  xxx | xxx |

Not developed anymore:

| Distro | Build dev | Build release | Stable release |
| --- | --- | --- | --- |
| ROS1 Noetic (u20.04) | [![Build Status](https://build.ros.org/job/Ndev__mrpt_sensors__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__mrpt_sensors__ubuntu_focal_amd64/) | [![Build Status](https://build.ros.org/job/Nbin_uF64__mrpt_sensors__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__mrpt_sensors__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/mrpt_sensors)](https://index.ros.org/search/?term=mrpt_sensors) |



### mola_common

https://github.com/MOLAorg/mola_common

| Distro | Develop branch | Releases | Stable release |
| ---    | ---            | ---      |  ---      |
| ROS2 Humble  (u22.04) |  [![Build Status](https://build.ros2.org/job/Hdev__mola_common__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mola_common__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_common__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_common__ubuntu_jammy_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/humble/mola_common)](https://index.ros.org/search/?term=mola_common) |
| ROS2 Iron  (u22.04)   |  [![Build Status](https://build.ros2.org/job/Idev__mola_common__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mola_common__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_common__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_common__ubuntu_jammy_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/iron/mola_common)](https://index.ros.org/search/?term=mola_common) |
| ROS2 Rolling (u22.04) | [![Build Status](https://build.ros2.org/job/Rdev__mola_common__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mola_common__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Rbin_uJ64__mola_common__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uJ64__mola_common__ubuntu_jammy_amd64__binary/)  | [![Version](https://img.shields.io/ros/v/rolling/mola_common)](https://index.ros.org/search/?term=mola_common) |



### MOLA

https://github.com/MOLAorg/mola

[![CI Check clang-format](https://github.com/MOLAorg/mola/actions/workflows/check-clang-format.yml/badge.svg)](https://github.com/MOLAorg/mola/actions/workflows/check-clang-format.yml)
[![CI ROS](https://github.com/MOLAorg/mola/actions/workflows/build-ros.yml/badge.svg)](https://github.com/MOLAorg/mola/actions/workflows/build-ros.yml)
[![CircleCI](https://img.shields.io/circleci/build/gh/MOLAorg/mola/develop.svg)](https://circleci.com/gh/MOLAorg/mola)
[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](https://docs.mola-slam.org/latest/)

| Distro | Build dev | Release |
| --- | --- | --- |
| ROS 2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mola__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mola__ubuntu_jammy_amd64/) | [![Version](https://img.shields.io/ros/v/humble/mola)](https://index.ros.org/search/?term=mola) |
| ROS 2 Iron (u22.04) | [![Build Status](https://build.ros2.org/job/Idev__mola__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__mola__ubuntu_jammy_amd64/) | [![Version](https://img.shields.io/ros/v/iron/mola)](https://index.ros.org/search/?term=mola) |
| ROS 2 Rolling (u24.04) | [![Build Status](https://build.ros2.org/job/Rdev__mola__ubuntu_noble_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mola__ubuntu_noble_amd64/) | [![Version](https://img.shields.io/ros/v/rolling/mola)](https://index.ros.org/search/?term=mola) |

#### MOLA binary packages


| Package | ROS 2 Humble <br/> BinBuild |  ROS 2 Iron <br/> BinBuild |  ROS 2 Rolling <br/> BinBuild |
| --- | --- | --- | --- |
| kitti_metrics_eval | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__kitti_metrics_eval__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__kitti_metrics_eval__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__kitti_metrics_eval__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__kitti_metrics_eval__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__kitti_metrics_eval__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__kitti_metrics_eval__ubuntu_noble_amd64__binary/) |
| mola | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola__ubuntu_noble_amd64__binary/) |
| mola_bridge_ros2 | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_bridge_ros2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_bridge_ros2__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_bridge_ros2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_bridge_ros2__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_bridge_ros2__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_bridge_ros2__ubuntu_noble_amd64__binary/) |
| mola_demos | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_demos__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_demos__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_demos__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_demos__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_demos__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_demos__ubuntu_noble_amd64__binary/) |
| mola_imu_preintegration | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_imu_preintegration__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_imu_preintegration__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_imu_preintegration__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_imu_preintegration__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_imu_preintegration__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_imu_preintegration__ubuntu_noble_amd64__binary/) |
| mola_input_euroc_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_euroc_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_euroc_dataset__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_input_euroc_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_input_euroc_dataset__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_euroc_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_euroc_dataset__ubuntu_noble_amd64__binary/) |
| mola_input_kitti360_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti360_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti360_dataset__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_input_kitti360_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_input_kitti360_dataset__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti360_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti360_dataset__ubuntu_noble_amd64__binary/) |
| mola_input_kitti_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti_dataset__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_input_kitti_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_input_kitti_dataset__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti_dataset__ubuntu_noble_amd64__binary/) |
| mola_input_mulran_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_mulran_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_mulran_dataset__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_input_mulran_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_input_mulran_dataset__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_mulran_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_mulran_dataset__ubuntu_noble_amd64__binary/) |
| mola_input_paris_luco_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_paris_luco_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_paris_luco_dataset__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_input_paris_luco_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_input_paris_luco_dataset__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_paris_luco_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_paris_luco_dataset__ubuntu_noble_amd64__binary/) |
| mola_input_rawlog | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_rawlog__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_rawlog__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_input_rawlog__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_input_rawlog__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_rawlog__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_rawlog__ubuntu_noble_amd64__binary/) |
| mola_input_rosbag2 | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_rosbag2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_rosbag2__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_input_rosbag2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_input_rosbag2__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_rosbag2__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_rosbag2__ubuntu_noble_amd64__binary/) |
| mola_kernel | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_kernel__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_kernel__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_kernel__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_kernel__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_kernel__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_kernel__ubuntu_noble_amd64__binary/) |
| mola_launcher | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_launcher__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_launcher__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_launcher__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_launcher__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_launcher__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_launcher__ubuntu_noble_amd64__binary/) |
| mola_metric_maps | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_metric_maps__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_metric_maps__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_metric_maps__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_metric_maps__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_metric_maps__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_metric_maps__ubuntu_noble_amd64__binary/) |
| mola_navstate_fuse | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_navstate_fuse__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_navstate_fuse__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_navstate_fuse__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_navstate_fuse__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_navstate_fuse__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_navstate_fuse__ubuntu_noble_amd64__binary/) |
| mola_pose_list | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_pose_list__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_pose_list__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_pose_list__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_pose_list__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_pose_list__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_pose_list__ubuntu_noble_amd64__binary/) |
| mola_traj_tools | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_traj_tools__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_traj_tools__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_traj_tools__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_traj_tools__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_traj_tools__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_traj_tools__ubuntu_noble_amd64__binary/) |
| mola_viz | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_viz__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_viz__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_viz__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_viz__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_viz__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_viz__ubuntu_noble_amd64__binary/) |
| mola_yaml | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_yaml__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_yaml__ubuntu_jammy_amd64__binary/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__mola_yaml__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__mola_yaml__ubuntu_jammy_amd64__binary/)| [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_yaml__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_yaml__ubuntu_noble_amd64__binary/) |


### gtsam

I maintain the ROS packaging of this awesome factor graph library, and made tiny contributions upstream.
Sources: https://github.com/borglab/gtsam/

| ROS distro | develop CI | Next build CI | Stable release |
|---|---|---|---|
| ROS 1 Noetic |  [![Build Status](https://build.ros.org/job/Ndev__gtsam__ubuntu_focal_amd64/badge/icon)](https://build.ros.org/job/Ndev__gtsam__ubuntu_focal_amd64/) | [![Build Status](https://build.ros.org/job/Nbin_uF64__gtsam__ubuntu_focal_amd64__binary/badge/icon)](https://build.ros.org/job/Nbin_uF64__gtsam__ubuntu_focal_amd64__binary/) | [![Version](https://img.shields.io/ros/v/noetic/gtsam)](https://index.ros.org/search/?term=gtsam) |
| ROS 2 Humble | [![Build Status](https://build.ros2.org/job/Hdev__gtsam__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__gtsam__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__gtsam__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__gtsam__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/humble/gtsam)](https://index.ros.org/search/?term=gtsam) | 
| ROS 2 Iron | [![Build Status](https://build.ros2.org/job/Idev__gtsam__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Idev__gtsam__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Ibin_uJ64__gtsam__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Ibin_uJ64__gtsam__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/iron/gtsam)](https://index.ros.org/search/?term=gtsam) |
| ROS 2 Rolling | [![Build Status](https://build.ros2.org/job/Rdev__gtsam__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Rdev__gtsam__ubuntu_jammy_amd64/) | [![Build Status](https://build.ros2.org/job/Rbin_uJ64__gtsam__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uJ64__gtsam__ubuntu_jammy_amd64__binary/) | [![Version](https://img.shields.io/ros/v/rolling/gtsam)](https://index.ros.org/search/?term=gtsam) |




