---
layout: post
title: Linux常用命令
date: 2024-09-15 11:01 +0800
img_path: "/../assets/img/pic"
image: head/cat.jpg
category:
- default
toc: true
comments: false
math: true
mermaid: true
hidden: false
pin: true
---

## shell内置命令和外部命令区别

| 内置命令 | 外部命令 | 
| :-----:| :----: | 
| 不需要创建子进程 | 在shell中创建子进程| 
| 一种shell内部操作 | 调用在/usr/bin中的程序 | 
| 速度快 | 速度慢 | 
| 数量少，通常与 Shell 的基本功能密切相关 | 数量多，功能复杂 | 
| 移植性好，跟随shell | 移植性差，取决于linux环境 | 


## 内置命令和外部命令区分
使用`type`命令查看
```shell
root@iZbp19rh4d6jcag5epp4hrZ:/usr/bin# type -a ls
ls is aliased to `ls --color=auto'
```
```shell
root@iZbp19rh4d6jcag5epp4hrZ:/usr/bin# type -a pwd
pwd is a shell builtin
pwd is /usr/bin/pwd
pwd is /bin/pwd
```


## 内置命令
* `pwd`
* `cd`
* `echo`
* `type`
* `alias`
* `history`


## 外部命令
* `netstat -ntlp`
Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships
* `ifconfig`
configure a network interface
* `free`
Display amount of free and used memory in the system
* `df`
report file system disk space usage
* `du`
estimate file space usage
* `uname -a`
print system information
* `hostname`
show or set the system's host name
* `who`
show who is logged on
* `ps -ef`
report a snapshot of the current processes.
* `top`
display Linux processes
* `nohup`
run a command immune to hangups, with output to a non-tty
* `kill`
send a signal to a process
* `mkdir`
make directories
* `rmdir`
Remove the DIRECTORY(ies), if they are empty.
* `mv`
move (rename) files
* `rm`
rm removes each specified file.  By default, it does not remove directories.
* `cp`
copy files and directories
* `ls -la`
list directory contents
* `clear`
clear the terminal screen
* `which`
which - locate a command
* `find`
find - search for files in a directory hierarchy
* `grep`
print lines that match patterns
* `touch`
change file timestamps
* `tail -n 10 file.txt`
output the last part of files
* `head -n 10 err.log`
output the first part of files
* `cat`
concatenate files and print on the standard output
* `less`
similar to more,but it starts up faster than text editors like vi
* `history`
History library is able to keep track of those input commands



## git命令
* `git`
the stupid content tracker


## vim命令