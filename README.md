# VSDIAT_Week0_Task
Week 0 task submission





//soc design flow 
In the week 0 lecture explained about SYSTEM ON CHIP(SOC)
STEP1:
o1: SPECIFICATIONS
-high level specifications written in c language .
-to compile the c code in linux we use the compiler like GCC.
STEP2:
O2:RTL DESIGN
-hardware described using rtl(verilog)
-processor and pheripherals are defined.
-output: gate level netlist,macros,analog inputs.
STEP3 : 
o3:SOC INTEGRTION
-Integration of processor ,pheripherals,macros and analog inputs.
-verified 01=02=03.
STEP4:
o4-FINAL CHIP
-Physical implementation
-verified 01=02=03=04


o1=02 (cmodel vs rtl)
o2=03 (rtl vs gate level netlist)
o3=o4 (gatelevel vs layout)


INSTALLATION OF YOSIS,IVERILOG,GTKWAVE
Installation Yosys

 sudo apt-get update
 git clone https://github.com/YosysHQ/yosys.git
 cd yosys
 sudo apt install make (If make is not installed please install it)
 sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
 make config-gcc
 make
 sudo make install

Installation of iverilog
sudo apt-get update
sudo apt-get install iverilog 

Installation of gtkwave
sudo apt-get update
sudo apt install gtkwave 



