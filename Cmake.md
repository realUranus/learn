#### official tutorial
https://cmake.org/cmake/help/v3.17/guide/tutorial/index.html


#### basic

#### add a executable
add_executable()
这意味着从一个或者几个文件生成可执行文件
clion会自动生成一个配置

#### add a library
add_library()
从文件生成lib
clion会自动生成一个配置

#### 编译类型和CMake profiles
编译类型：debug或者release
在build的时候，选择不同选项，就会生成到不同的目录。

#### 增加include目录
include_directories()

#### 链接库
find_library()
target_link_libraries()

#### Boost 引入
https://cmake.org/cmake/help/v3.15/module/FindBoost.html
首先要用find_package()指明Boost和版本，如果有组件，还要指明组件
然后再用target_link_libraries()将组件和目标链接起来。








