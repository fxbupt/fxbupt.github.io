---
layout: post
title: Install Redis on Windows 7
---
1、安装Windows下的包管理工具 Chocolatey;
2、在命令行工具下执行命令 choco install redis-64;
3、cd C:\ProgramData\chocolatey\lib\redis-64;
4、redis-server redis.windows.conf;
5、再打开另一命令行，执行 redis-cli;
