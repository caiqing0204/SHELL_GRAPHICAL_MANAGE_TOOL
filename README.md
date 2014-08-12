SHELL_GRAPHICAL_MANAGE_TOOL
===========================

shell + dialog
如题这一个用dialog+shell的图形化管理工具（CENTOS）。
-----------------------------------
###大致有以下几个功能：
1）生成主机报告信息
    1.1）主机软件信息（如：主机名、系统版本、内核版本、系统负荷）
    1.2）网络信息（如：IP配置、MAC地址）
    1.3）账户安全（如：查看能登入系统的用户、已登入的用户、失败超过三次的IP，并查询IP所在地）
    1.4）硬件信息（如：查看CPU，内存，磁盘，服务器序列号）
2）网络管理
    2.1）配置IP地址
    2.2）添加网关
    2.3）配置DNS
    2.4）查看网卡速率
3）安装功能
    3.1）安装LAMP
    3.2）安装LNMP
    3.3）安装系统管理工具（如：iftop，iotop，strace等等）
4）服务配置
    4.1）服务配置（如：apache、nginx、mysql、PHP模块、防火墙配置）
    4.2）开启关闭selinux
    4.3）开启/关闭LAMP
    4.4）开启/关闭LNMP
5）磁盘测试
    5.1）测试写入速度（暂未实现）
    5.2）测试读取速度
6）远程命令
7）数据备份
    7.1）备份源代码
    7.2）备份数据库（如：导入mysql、备份mysql）

如何使用？
# bash main.sh

格式全乱了。