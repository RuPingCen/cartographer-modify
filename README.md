# 说明

该代码是参考 google cartographer 官方网站安装编译的（https://google-cartographer-ros.readthedocs.io/en/latest/compilation.html）

由于国内网络的原因，在安装cartographer 的时候我们需要做一些修改。

1. 在执行命令 （wstool merge -t src https://raw.githubusercontent.com/googlecartographer/cartographer_ros/master/cartographer_ros.rosinstall） 的时候我们需要修改 .rosinstall 文件，将 ceres-solver地址为 （https://github.com/ceres-solver/ceres-solver.git）




