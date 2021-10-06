1.下载代码：

$git clone https://gitclone.com/github.com/littlevgl/pc_simulator.git
$cd pc_simulator
$git submodule update --init
2.编译：

2.在pc_simulator目录下，执行：

make

3.测试，验证：

在pc_simulator目录下，执行 ./demo

问题
1，没有安装SDL2，需要安装

执行这两个命令就可以了
sudo apt-get install libsdl2-2.0
sudo apt-get install libsdl2-dev
引用SDL2库编译自己的程序
gcc -o myprogram myprogram.c `sdl2-config --cflags --libs`


4.Debug littleVGL

 修改Makefile，-g3 增加调试信息


