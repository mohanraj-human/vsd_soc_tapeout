## Yosys
```bash
$ sudo apt-get update 
$ git clone [https://github.com/YosysHQ/yosys.git](https://github.com/YosysHQ/yosys.git) 
$ cd yosys 
$ sudo apt install make (If make is not installed please install it)  
$ sudo apt-get install build-essential clang bison flex \ 
  libreadline-dev gawk tcl-dev libffi-dev git \ 
  graphviz xdot pkg-config python3 libboost-system-dev \ 
  libboost-python-dev libboost-filesystem-dev zlib1g-dev 
$ make config-gcc 
$ make  
$ sudo make install
```
![image alt](https://github.com/mohanraj-human/vsd_soc_tapeout_week0/blob/main/screenshots/yosys.png)

## Iverilog
```bash
$sudo apt-get install iverilog
```
![image alt](https://github.com/mohanraj-human/vsd_soc_tapeout_week0/blob/main/screenshots/iverilog.png)

## GtkWave
```bash
$ sudo apt install gtkwave
$ gtkwave
```
![image alt](https://github.com/mohanraj-human/vsd_soc_tapeout_week0/blob/main/screenshots/gtkwake.png)
