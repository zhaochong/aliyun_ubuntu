# 这里搜集了 ubuntu 的 apt-get 源，可以加速国内的 apt-get 使用
使用方法：

sudo cp /etc/apt/sources.list /etc/apt/sources.list.back

git clone https://github.com/zhaochong/sourcelist.git 

sudo cp sourcelist/* /etc/apt/sources.list.d

sudo apt-get update


