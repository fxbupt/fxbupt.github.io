---
layout: post
title: Install Redis on Windows 7
---
- 安装Windows下的包管理工具 Chocolatey;
- 在命令行工具下执行命令 choco install redis-64;
- cd C:\ProgramData\chocolatey\lib\redis-64;
- redis-server redis.windows.conf;
- 再打开另一命令行，执行 redis-cli;
