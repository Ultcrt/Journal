UTF-8报错：#!/usr/bin/python
                   #coding:utf-8
                  （代码中添加）

找不到指令：在./.local/bin中找到程序同名文件，在/etc/profile末尾加入：
                    export PATH=$PATH:~/.local/bin
                    之后执行：source /etc/profile