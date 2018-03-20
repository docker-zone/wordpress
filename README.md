# 前言
	使用docker-compose一键安装wordpress。

# 使用指南
	首先请确保安装了docker-compose,如未安装，执行命令pip install docker-compose安装。
	然后复制wordpress_create.yml文件到宿主机上，执行docker-compose -p cms -f wordpress_create_yml up -d
	最后访问http://ip:8080即可