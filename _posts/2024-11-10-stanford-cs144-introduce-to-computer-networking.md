---
layout: post
title: CS144-Introduce to Computer Networking（2024winter）
date: 2024-11-10 06:03 +0800
img_path: "/../assets/img/pic"
image: head/hdu.jpeg

description: Short summary of the post.

toc: true
comments: false

math: true
mermaid: true

# hidder this post or not on the home page
hidden: false
# pin one or more posts to the top of the home page
pin: true
categories: [CS自学课程,Stanford University]
---

## 环境配置

### [课程推荐配置](https://stanford.edu/class/cs144/vm_howto/)
1. On Intel/AMD computers: 
Use a [VM image](https://stanford.edu/class/cs144/vm_howto/vm-howto-image.html) that we prepared in VirtualBox
> 没有测试
2. Use a Google Cloud virtual machine using our class’s coupon code(
instructions at <https://stanford.edu/class/cs144/vm_howto>)
> 没有测试
3. On ARM MacBooks and Macs: 
please install the UTM virtual machine software and use our [ARM64 GNU/Linux virtual machine image](https://web.stanford.edu/class/cs144/vm_files/cs144-arm64-2024.utm.tar.gz)
> 经测试，无法顺利安装

### 环境要求
1. GNU/Linux系统，最好是**Ubuntu version 23.10**
2. C++编译器支持**C++ 2020 standard**，例如**g++13.2**

### 我的环境
* 硬件MacbookAir-2020(Arm64 M1芯片)
* 虚拟机软件Vmware Fusion
* Ubuntu 24.04.1 LTS (GNU/Linux 6.8.0-48-generic aarch64)

### 环境安装
* 软件包安装
```terminal
yan@ubuntu24:~$ sudo apt update && sudo apt install git cmake gdb build-essential clang \
            clang-tidy clang-format gcc-doc pkg-config glibc-doc tcpdump tshark
```