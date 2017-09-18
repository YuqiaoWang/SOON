# SOON开发日志
## 2017.9.18
1. 关于新版 ONOS 编译安装

ONOS-1.8 版本起强制使用 BUCK 构建工具，不再使用 maven，编译和打包方式与旧版本有所区别

步骤：  
配置环境 -> 下代码 -> 编译 -> 运行
<pre><code>
编译命令
$ONOS_ROOT/tools/build/onos-buck build onos --show-output
编译后生成一个.tar.gz 的包（编译完成后有提示包在哪个目录下）

运行命令
将.tar.gz包解压在一个目录下，在该路径下执行
apache-karaf-3.0.8/bin/karaf
即可运行ONOS
</code></pre>

2. 关于 TensorFlow 的调研
- TensorFlow 提供的 java API


- 用 ONOS 的 APP 启动 python, 用 python 跑 TensorFlow


- 把 TensorFlow 写进ONOS的 OSGI 库里


