

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




