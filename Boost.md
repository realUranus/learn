#### log
##### Design overview
###### logging sources



#### program options
如何查看示例：
官方说示例可以在"BOOST_ROOT/libs/program_options/example"下面找到。
但是这个boost_root在系统里没有。
1. 本地：/usr/share/doc/libboost-doc/examples/libs/program_options
2. 网络：http://www.boost.org/doc/libs/1_71_0/libs/program_options/example/（版本号可变）
文档的内容默认安装到/usr/share/doc/

##### 错误undefined reference to `boost::program_options::o
在编译的时候加上链接：-lboost_program_options
别的错误就对应修改即可


