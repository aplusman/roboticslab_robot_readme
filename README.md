# 防疫機器人
* updated on May 18, 2023

### Introduction

* sensor list: RealSense2, 3D LiDAR, 2D LiDAR
* 定義前方: RealSense2看到的方向
* 左邊電池供電: 3D LiDAR, 螢幕
* 右邊電池供電: 工業電腦

### Procedure
(1) 接上24V的power接口 (黃色label) \
(2) 開啟工業電腦的power (藍色label) \
(3) 開啟3D LiDAR的power (紫色label) \
(4) 開啟防疫機器人側邊黃色按鈕 \
(5) 打開工業電腦 (red按鈕) \
(6) ```cd ~/Desktop/dashgo/dashgo_ws/``` \
(7) ```source devel/setup.zsh``` \
(8) ```roslaunch overall_system record_all.launch```

### Attachment
* ```lslidar_c16_0515.tar.xz``` for the Leishen LiDAR driver

