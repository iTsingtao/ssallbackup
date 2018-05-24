# ssallbackup
# 个人备份使用，以应对可能出现的原作者（秋水逸冰博主）受不可抗力删除项目的情况。

# CentOS 6+，Debian 7+，Ubuntu 12+ required (linux)
# install way 1
wget -N --no-check-certificate https://raw.githubusercontent.com/Ache1123/ssallbackup/master/shadowsocks-all.sh && chmod +x shadowsocks-all.sh && bash shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
# install way 2
apt-get update   
apt-get install git -y    
git clone https://github.com/Ache1123/ssallbackup   
cd ssallbackup     
chmod +x shadowsocks-all.sh   
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log  
# uninstall way
./shadowsocks-all.sh uninstall
# BBR
BBR in ssrmubackup can be deployed independently
