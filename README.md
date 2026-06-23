# NanoBot_SDK

***A repo. which maintains sensor pkgs for NanoBot.***

- **fdilink_ahrs**: for FDISYSTEMS Deta10 9-axis IMU, validated VINS-Mono system using a low-price global-shutter gray camera.
- **icm20948**: for DIY 9-axis IMU using ICM-20948.
- **lakibeam1**: for RichBeam LakiBeam1L 2D LiDAR.

## Run

```bash
mkdir -p NanoBot/src
cd NanoBot/src
git clone git@github.com:zhan994/nanobot_sdk.git
cd ..
catkin_make
```
