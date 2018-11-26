UTF-8报错：#!/usr/bin/python
                   #coding:utf-8
                  （代码中添加）

找不到指令：在./.local/bin中找到程序同名文件，在/etc/profile末尾加入：
                    export PATH=$PATH:~/.local/bin
                    之后执行：source /etc/profile

显示隐藏文件：ctrl+h

'chromedriver' executable needs to be in PATH报错：由于chromedriver安装目录为/usr/lib/chromium-browser，而qqbot识别路径为usr/bin而导致
                                                                                 输入：cd /usr/lib/chromium-browser
                                                                                           sudo cp chromedriver /usr/bin