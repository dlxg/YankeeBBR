# YankeeBBR
来自Loc大佬Yankee魔改的BBR的Debian一键安装包

一键安装:  
wget -N --no-check-certificate https://raw.githubusercontent.com/FunctionClub/YankeeBBR/master/bbr.sh && bash bbr.sh install

安装后重启vps执行:  
bash bbr.sh start

查看魔改BBR状态:  
sysctl net.ipv4.tcp_available_congestion_control

如果看到有 tsunami 就表示开启成功！
