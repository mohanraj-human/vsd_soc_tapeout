## Yosys
```bash
$ sudo apt-get update 
$ git clone [https://github.com/YosysHQ/yosys.git](https://github.com/YosysHQ/yosys.git) 
$ cd yosys 
$ sudo apt install make
$ sudo apt-get install build-essential clang bison flex \ 
  libreadline-dev gawk tcl-dev libffi-dev git \ 
  graphviz xdot pkg-config python3 libboost-system-dev \ 
  libboost-python-dev libboost-filesystem-dev zlib1g-dev 
$ make config-gcc 
$ make  
$ sudo make install
```
![image alt](https://github.com/mohanraj-human/vsd_soc_tapeout/blob/main/week0/screenshots/yosys.png)

## Iverilog
```bash
$sudo apt-get install iverilog
```
![image alt](https://github.com/mohanraj-human/vsd_soc_tapeout/blob/main/week0/screenshots/iverilog.png)

## GtkWave
```bash
$ sudo apt install gtkwave
$ gtkwave
```
![image alt](https://github.com/mohanraj-human/vsd_soc_tapeout/blob/main/week0/screenshots/gtkwake.png)
