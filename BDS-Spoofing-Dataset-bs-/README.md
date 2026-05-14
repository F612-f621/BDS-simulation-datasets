# BDS-Spoofing-Dataset-bs-
 The datasets contain seven mixed scenarios (bs1–bs7) including intermediate frequency signals, 5G system pseudorange and angle-of-arrival observations generated per second for two base stations, and three-dimensional angular increments and velocity increments output by INS sensors of three different accuracy grades at each update cycle (5 ms).



信号参数配置：
IF：0 MHz
Fs：5 MHz
complex：Yes
TimeLength：220s

轨迹文件：circle.csv、trajectory_ENU.mat、trajectory_XYZ.mat (0-220s)

5gData：
results_5G：依次保存了2个LoS基站每个历元的测距测角结果，每个基站保存的信息为：
[cellid1 BSPos_XYZ1 BSPos_ENU1 distance_true distance_ssb distance_prs elevation_ture azimuth_true elevation_esti azimuth_esti]

imuData中包含了四个文件:
Origin_imu.mat: 不加INS误差，陀螺仪输出的三维角度增量、加速度计输出的三维速度增量，最后一列为惯导更新时间
Consumer_grade_imu.mat: 加消费级INS误差，陀螺仪输出的三维角度增量、加速度计输出的三维速度增量，最后一列为惯导更新时间
Tactical_grade_imu.mat: 加战术级INS误差，陀螺仪输出的三维角度增量、加速度计输出的三维速度增量，最后一列为惯导更新时间
Aviation_grade_imu.mat: 加航空级INS误差，陀螺仪输出的三维角度增量、加速度计输出的三维速度增量，最后一列为惯导更新时间

数据集访问：
使用者可以通过百度网盘进行访问，并从中完成下载：
通过网盘分享的文件：bds_spoof_dataset
链接: https://pan.baidu.com/s/1LyqiSr8e3DTaJPULSnX0EQ 提取码: 2s9a 


Signal Parameter Configuration:
IF: 0 MHz
Fs: 5 MHz
complex: Yes
TimeLength: 220s

Trajectory Files: circle.csv, trajectory_ENU.mat, trajectory_XYZ.mat (0-220s)

5gData:
results_5G: Sequentially saves the ranging and angle measurement results for each epoch of two LoS ​​base stations. The information saved for each base station is:
[cellid1 BSPos_XYZ1 BSPos_ENU1 distance_true distance_ssb distance_prs elevation_ture azimuth_true elevation_esti azimuth_esti]

imuData contains four files:
Origin_imu.mat: Without INS error, the 3D angle increment output by the gyroscope, the 3D velocity increment output by the accelerometer, and the last column is the inertial navigation update time.
Consumer_grade_imu.mat: Adding consumer-grade INS error, the 3D angle increment from the gyroscope output and the 3D velocity increment from the accelerometer output are shown in the last column, which is the INS update time.
Tactical_grade_imu.mat: Adding tactical-grade INS error, the 3D angle increment from the gyroscope output and the 3D velocity increment from the accelerometer output are shown in the last column, which is the INS update time.
Aviation_grade_imu.mat: Adding aviation-grade INS error, the 3D angle increment from the gyroscope output and the 3D velocity increment from the accelerometer output are shown in the last column, which is the INS update time.

Dataset Access: Users can access and download the dataset via Baidu Cloud.
File shared via Baidu Cloud: bds_spoof_dataset
Link: https://pan.baidu.com/s/1LyqiSr8e3DTaJPULSnX0EQ Extraction code: 2s9a
