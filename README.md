# AMH4.2-XB
AMH4.2修改，配置可选
##初始
* ####建议先保证初始命令

    yum update -y
    yum install -y wget
    yum install -y vim
    
* ####强烈建议先运行screen,防止ssh中断

    apt-get install screen #(debian)
    
    yum -y install screen #(centos)
    
    screen -S amh
    
更新curl为curl-7.53.0 （如果内存没超过1G以上，不建议安装Mysql5.7以及以上系列数据库）
更新：php-5.3.29，php-5.4.45，php-5.5.38，php-5.6.30，php-7.1.1，nginx-1.10.3，openssl-1.1.0e，mysql-5.5.54，mysql-5.6.35，mysql-5.7.17，mariadb-5.5.54，mariadb-10.1.21。

* ####Centos 5 .x 和 Centos 6.x安装脚本

    wget https://raw.githubusercontent.com/Huiaini/AMH4.2-XB/master/amh4.2.sh
    chmod 775 amh.sh
    ./amh.sh 2>&1 | tee amh.log 
    
* ####Centos 7.x安装脚本
请先运行ifconfig，要是功能不全，

* ####请先yum安装

    yum -y install net-tools.x86_64
    
* ####然后再运行安装脚本

    wget https://raw.githubusercontent.com/Huiaini/AMH4.2-XB/master/amh4.2.sh
    chmod 775 amh.sh
    ./amh.sh 2>&1 | tee amh.log
    
<br>
<br>
    感谢[静夜思雨](https://www.sxsay.com/364.html)脚本
