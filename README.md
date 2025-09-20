# VSDIAT_Week0_Task
Week 0 task submission
RISC-V Reference SoC Tapeout Program VSD



























## SoC Design Flow

### Step 1: Specifications
- High-level specs written in C.
- Compiled in Linux using GCC.

### Step 2: RTL Design
- Hardware described in Verilog.
- Processor + peripherals defined.
- Output: gate-level netlist, macros, analog inputs.

### Step 3: SoC Integration
- Integration of processor, peripherals, macros, and analog inputs.
- Verified equivalence between steps.

### Step 4: Final Chip
- Physical implementation.
- Verification ensures consistency from C model → RTL → netlist → layout.







## Tool Installation

##yosys
```bash
sudo apt-get update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make build-essential clang bison flex \
  libreadline-dev gawk tcl-dev libffi-dev git \
  graphviz xdot pkg-config python3 libboost-system-dev \
  libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make
sudo make install





##Icarus Verilog (iverilog)

sudo apt-get update
sudo apt-get install iverilog

##GTKWave
sudo apt-get update
sudo apt install gtkwave






