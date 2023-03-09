# front-end-operations-study
前端运维学习 Linux是一套免费使用和自由传播的类Unix操作系统 在服务器端领域和嵌入式领域有非常广泛的应用


Linux严格区分大小写
Linux中所有的内容以文件形式保存，包括硬件、用户和文件。
Linux不靠扩展名区分文件类型，是靠权限来区分，但是有一些约定的扩展名，是给管理员看的
压缩包 .gz .bz2 .tar.bz2 .tgz
二进制文件 .rpm
网页文件 .html .php
脚本文件 .sh
配置文件 .conf
Windows下的程序不能直接在Linux中安装和运行
Linux更多使用字符界面
占用的系统资源更少
减少了出错和被攻击的可能性，会让系统更稳定

常见目录：
目录	用途
/	    根目录
/boot	启动目录，启动相关文件
/dev	设备文件
/etc	配置文件
/home	普通用户的家目录,可以操作
/lib	系统库保存目录
/mnt	移动设备挂载目录
/media	光盘挂载目录
/misc	磁带机挂载目录
/root	超级用户的家目录,可以操作
/tmp	临时目录,可以操作
/proc	正在运行的内核信息映射, 主要输出进程信息、内存资源信息和磁盘分区信息等等
/sys	硬件设备的驱动程序信息
/var	变量
/bin	普通的基本命令，如ls,chmod等,一般的用户也都可以使用
/sbin	基本的系统命令，如shutdown，reboot，用于启动系统，修复系统,只有管理员才可以运行
/usr/bin	是你在后期安装的一些软件的运行脚本
/usr/sbin	放置一些用户安装的系统管理的必备程序