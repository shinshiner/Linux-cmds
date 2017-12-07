* 统计网络吞吐量： `sudo iptables -vxn -L`
* 统计网络吞吐量并写入文件： `sudo iptables -vxn -L | awk \'{print $2}\' >> filename`
