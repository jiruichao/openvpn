# 源码编译安装openvpn（适用于ubuntu）

    apt-get -y install ca-certificates gcc build-essential libssl-dev liblzo2-dev liblzo2-2 libpam-dev liblz4-dev liblzo2-dev libpam-dev
    apt-get -y install make
    apt-get -y install make-guile
    tar -xf openvpn-2.4.7.tar.gz
    cd openvpn-2.4.7
    ./configure
    make -j 8 && make install
    rm -rf openvpn-2.4.7
    openvpn --version
