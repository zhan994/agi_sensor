# icm20948

Step1: clone this package to your workspace/src fold

Step2: catkin_make your workspace

Step3: roscd icm20948/script/

Step4: sudo ./udev.sh

Step5: connect IMU device to your PC via USB cable

Step6: roslaunch icm20948 sensor_imu.launch

Now you can get /imu and /mag topic

Note:Step 1~4 need do only once when you install this package

Change NOTE:
add imu data mode switch,default is gravity mode,launch use roslaunch sensor_imu sensor_imu.launch gravity:=false can out put none gravity imu data(x,y,z line accel is zero when static or constant speed)
