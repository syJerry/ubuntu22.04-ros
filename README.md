# ubuntu22.04-ros
ubuntu2022安装ros1
安装过程参考了https://github.com/lesaf92/ros_noetic_ubuntu22/blob/main/README.md
记录一下
1.安装成功后后续所有操作都要在ros_env的环境下进行
conda activate ros_env
2.安装库的命令
conda install -c robostack <package>
例如conda install -c robostack ros-noetic-move-base
