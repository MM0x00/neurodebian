# neurodebian 在线实验环境

## 软件简介

软件基本信息，License，所属的类别，作用，特点等。
NeuroDebian为Debian操作系统以及Ubuntu等衍生产品提供了大量流行的神经科学研究软件。热门套餐包括AFNI，FSL，PyMVPA，等等。虽然我们努力保持高水平的质量，但我们不保证给定的包装按预期工作，所以使用它们自己承担风险。

所属类型是操作系统



## 软件官网

http://neurodebian.ovgu.de/

## Dockerfile 使用方法

sources.list

NeuroDebian APT文件安装在档案下方/etc/apt/sources.list.d/neurodebian.sources.list，目前仅允许main（DFSG兼容）存档：
```
$ docker run neurodebian:latest cat /etc/apt/sources.list.d/neurodebian.sources.list
deb http://neuro.debian.net/debian wheezy main
deb http://neuro.debian.net/debian data main
#deb-src http://neuro.debian.net/debian-devel wheezy main
```
## 资源链接

- http://neurodebian.ovgu.de/
