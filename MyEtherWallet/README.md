Address
=======

0x8378419AbBd96dE88091caf5c4A7d8507DCe0423


Create Ubuntu1604 CPU Miner
===========================

```bash
$ sed -i 's/archive.ubuntu.com/tw.archive.ubuntu.com/g' /etc/apt/sources.list

$ apt-get update

$ apt-get -y install git

$ apt-get -y install automake autoconf pkg-config libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev make g++

$ git clone https://github.com/tpruvot/cpuminer-multi

$ cd cpuminer-multi/
$ ./build.sh
$ ./cpuminer-multi -a 
```


```bash
$ sed -i 's/archive.ubuntu.com/tw.archive.ubuntu.com/g' /etc/apt/sources.list

$ apt-get update

$ apt-get -y install libmicrohttpd-dev libssl-dev cmake build-essential

$ git clone https://github.com/fireice-uk/xmr-stak-cpu.git
$ cd xmr-stak-cpu/
$ cmake .
$ make install
```