#### cmake
##### 

##### cmake practice
http://file.ncnynl.com/ros/CMake%20Practice.pdf

#### G++
##### No such file or directory
明明在/usr/local/lib里面有so文件，而且路径也在/etc/ld.so.conf文件里面，怎么就是找不到这个库呢？
解决：执行sudo ldconfig刷新一下

#### 问题搜集
##### 如何查看安装的软件或者包的路径
比如查看boost，boost是通过apt安装的。
安装的指令是：apt install libboost-dev
使用：whereis boost即可
