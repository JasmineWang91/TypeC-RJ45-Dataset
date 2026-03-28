# TypeC-RJ45 Assembly Dataset

This repository provides the **TypeC-RJ45 Assembly Dataset**, designed to support research in robotic connector assembly through 6-DOF tactile force signals.

## 🔍 Overview

We design and conduct robotic assembly experiments using **USB Type-C** and **RJ45 Ethernet** connectors to simulate connector assembly processes commonly performed in industrial automation. These connectors differ significantly in their mechanical structures and insertion dynamics, making them suitable for evaluating model generalization across connector types.

The dataset is used to evaluate the performance of the proposed **DynMIL-Lite** model for mating detection in robotic connector assembly tasks.

### Assembly Video
- [Experimental Videos](https://www.dropbox.com/scl/fo/3q5uhdq1p4gby9xvyi2td/AEwmypNkR3_pncUiJnPhJe4?rlkey=5nxtxcyr7xsrehqy2u1l6wc33&st=677an3ob&dl=0)

## 📦 Dataset Contents

The dataset contains two files:

- **`Typec_data.npz`**: 6-DOF force-torque time series data collected during robotic assembly of USB Type-C connectors.
- **`RJ45_Ethernet_dat.npz`**: 6-DOF force-torque time series data collected during robotic assembly of RJ45 Ethernet connectors.

Each `.npz` file includes multiple assembly trials. For each trial, it records time-series data from a force-torque sensor capturing:

- Fx, Fy, Fz (Forces in 3 axes)
- Tx, Ty, Tz (Torques in 3 axes)

## 🧪 Experimental Setup

- **Connectors**: USB Type-C and RJ45 Ethernet
- **Sensor**: 6-DOF force-torque sensor mounted on the robot end-effector
- **Task**: Robotic insertion of the connector into its matching port
- **Goal**: To detect successful early mating conditions based on force-torque feedback

The experiments are carried out under controlled robotic manipulation conditions, allowing repeatable and systematic data collection.

## 📥 Download

You can download the full dataset from Dropbox:

🔗 [Download TypeC-RJ45 Dataset (Dropbox)](https://www.dropbox.com/scl/fo/gx7gefprtg79ge6q6jekx/AEhVqPxkwcmkBGSqrnh4BQw?rlkey=wq10q2un9cicv3v80n8y5dpcx&st=pb9cmc0a&dl=0)

The dataset includes:
- `Typec_data.npz`
- `RJ45_Ethernet_dat.npz`
