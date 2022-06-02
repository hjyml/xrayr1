# XRayR

一键脚本安装

wget -N https://raw.githubusercontent.com/hjyml/xrayr1/master/install.sh && bash install.sh

git clone https://github.com/hjyml/xrayr1 XrayR-release

国内机子加速

git clone https://ghproxy.com/https://github.com/hjyml/xrayr1 XrayR-release

wget -N https://ghproxy.com/https://raw.githubusercontent.com/hjyml/xrayr1/master/install.sh && bash install.sh

#docker安装

yum install -y yum-utils

yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo
    
yum install docker-ce docker-ce-cli containerd.io -y

yum clean all

rpm --rebuilddb

yum install docker-ce docker-ce-cli containerd.io -y

systemctl start docker

systemctl enable docker


curl -fsSL https://get.docker.com | bash -s docker

curl -L "https://github.com/docker/compose/releases/download/1.26.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

chmod +x /usr/local/bin/docker-compose

yum -y install git

git clone https://ghproxy.com/https://github.com/hjyml/xrayr1 XrayR-release

cd XrayR-release









