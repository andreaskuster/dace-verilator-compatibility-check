# dace-verilator-compatibility-check ![DaCe Verilator Compatibility Check](https://github.com/andreaskuster/dace-verilator-compatibility-check/workflows/DaCe%20Verilator%20Compatibility%20Check/badge.svg?branch=main)

## Compilation Commands

sudo apt-get install git make autoconf g++

git clone https://github.com/verilator/verilator 

cd verilator

git checkout v{version}

autoconf
./configure
make
sudo make install


## Get available versions/tags

https://api.github.com/repos/verilator/verilator/tags
