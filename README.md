# dace-verilator-compatibility-check [![Build Status](https://travis-ci.com/andreaskuster/dace-verilator-compatibility-check.svg?branch=main)](https://travis-ci.com/github/andreaskuster/dace-verilator-compatibility-check)

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
