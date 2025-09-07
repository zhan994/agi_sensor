Please follow the steps here:

```bash
# Put the folder of source code into `{your_catkin_workspace}/src`
cd {your_catkin_workspace}
catkin_make
source {your_catkin_workspace}/devel/setup.bash

# config RJ45 Network PC static_ip 192.168.198.1/24, then run Laserscan node: 
roslaunch lakibeam1 lakibeam1_scan.launch
# run Laserscan node with rviz view: 
roslaunch lakibeam1 lakibeam1_scan_view.launch
# run PointCloud2 node:
roslaunch lakibeam1 lakibeam1_pcd.launch
# run PointCloud2 node with rviz view:
roslaunch lakibeam1 lakibeam1_pcd_view.launch
# run Laserscan with icm20948
roslaunch lakibeam1 lakibeam1_icm20948.launch
```