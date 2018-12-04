安装selenium : pip install selenium
使用此网址：https://launchpad.net/
搜索chromium-browser armhf（目前最新版为：70.0.3538.67[到2018.11.26为止]）
使用指令：wget [deb下载地址]进行下载。
使用指令：sudo dpkg -i [deb名]进行安装。
安装完会显示depenency problem，此时使用apt-get install（修复安装指令）指令可以查询到缺失环境（笔者缺少的是chromium-codecs-ffmpeg与chromium-codecs-ffmpeg-extra）。
到launchpad的chromium-browser armhf网页中的Built files项，找到对应的确实环境下载安装（方法同上）。
chromium-chromedriver安装同上。