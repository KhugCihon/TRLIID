# TRLIID
## Twin Robot LiDAR Inertial Indoor Dataset

## 1. Introduction
**TRILIID** is a twin robot LiDAR inertial indoor dataset which is collected in Digital building, Kumoh national institute of technology. It consists of sequences of two different paths that contain dynamic objects.
Data was collected by attaching 'RPLIDAR A3' and 'IntelliThings IAHRS' sensors to Turtlebot 2e.
This dataset was collected by **Multi Agent System Laboratory(MASL)**.

### 1.1 Hardware setting
<div align="center">
    <img src="img/fig1.png" width = 100% >
</div>

## 1.2 Floor Plan
<div align="center">
    <img src="img/Digital_building_2nd_floor.jpg" width = 100% >
</div>

### 1.3 Floor plan with robot paths
<div align="center">
    <img src="img/fig2.png" width = 100% >
</div>

### 1.4 Real environments
<div align="center">
    <img src="img/fig3.png" width = 100% >
</div>

### 1.5 Point-by-point coordinates(m)
* **Robot1 starting point** : 0, 0
* **Robot2 starting point** : 0, -0.61
* **1st point** : -23.675(±0.219), -4.305(±0.066)
* **2nd point** : 39.825(±0.313), -4.455(±0.071)
* **3rd point** : 39.825(±0.313), -47.355(±0.306)

The values in parentheses next to the measurements indicate the error range.


## 2 IMU Intrinsics
### Robot1.
|   | Bias | Scale | temp. Coef. |
|:---|---:|---:|---:|
| Acceleration X | -0.001136 | 0.999263 | -0.000137 |
| Acceleration Y | 0.002839 | 0.998257 | 0.000084 |
| Acceleration Z | -0.004870 | 0.992874 | -0.001228 |
| Gyroscope X | 0.000359 | 1.003551 | -0.000457 |
| Gyroscope Y | -0.003104 | 0.999532 | -0.000005 |
| Gyroscope Z | -0.001310 | 0.999988 | 0.000071 |
| Magnetometer X | -78.237358 | 0.553163 | 0.133072 |
| Magnetometer Y | 8.084065 | 0.685189 | 0.103193 |
| Magnetometer Z | 3.329172 | 0.573119| 0.242445 |

### Robot2.
|   | Bias | Scale | temp. Coef. |
|:---|---:|---:|---:|
| Acceleration X | 0.009735 | 0.998774 | -0.000063 |
| Acceleration Y | 0.001534 | 0.997756 | 0.000114 |
| Acceleration Z | 0.004931 | 0.988787 | -0.002165 |
| Gyroscope X | -0.001612 | 1.011938 | -0.000388 |
| Gyroscope Y | -0.004843 | 1.024336 | 0.000047 |
| Gyroscope Z | 0.005711 | 1.022235 | -0.000056 |
| Magnetometer X | -32.725479 | 1.186119 | 0.059512 |
| Magnetometer Y | -14.910945 | 1.137707 | 0.081744 |
| Magnetometer Z | -5.648197 | 1.166337 | 0.369521 |

## 3. Downloads
[Robot1](https://drive.google.com/file/d/1zpWLjJqXGFoH4Dj3BS-4gPG8F3wSeYS0/view?usp=drive_link)

[Robot2](https://drive.google.com/file/d/14ZrPJYjsaBV-Q2BVdsGJGO-SLdBxFuNP/view?usp=drive_link)

## 4. Paper
Will be added soon.

## Acknowledgement
This research was supported by Korea Institute of Marine Science & Technology Promotion(KIMST) funded by the Ministry of Trade, Industry and Energy in 2023 (Project Number 20210630)
