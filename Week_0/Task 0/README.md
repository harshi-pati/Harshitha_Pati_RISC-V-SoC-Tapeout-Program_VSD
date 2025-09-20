# 📘 Tools Installation Guide 

## 🖥️ System Requirements

Minimum specifications:

* **Operating System:** Ubuntu 20.04 or later
* **Memory (RAM):** 6 GB or higher
* **Storage:** 50 GB available disk space
* **Processor:** 4 vCPUs

---

## 🔧 Tools to be Installed

1. **Yosys** – Open-source RTL synthesis framework
2. **Icarus Verilog (iverilog)** – Verilog simulation tool
3. **GTKWave** – Waveform visualization tool

---

## 📥 Installation and Verification

### 1. Install **Yosys**

```bash

sudo apt-get update                                       # Update system packages
                                   
git clone https://github.com/YosysHQ/yosys.git            # Clone Yosys repository
cd yosys

sudo apt install make build-essential clang bison flex \  # Install dependencies
libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 \
libboost-system-dev libboost-python-dev \
libboost-filesystem-dev zlib1g-dev

make config-gcc                                           # Build and install Yosys
make
sudo make install

yosys                                                     # Verify 
```

### Verification:

<img width="985" height="255" alt="Image" src="https://github.com/user-attachments/assets/f5ee6cfb-d2e8-4e95-9d31-0e55b3b8428f" />

---

### 2. Install **Icarus Verilog (iverilog)**

```bash

sudo apt-get update                                     # Install Icarus Verilog
sudo apt-get install iverilog

iverilog -V                                             # Verify installation
```
### Verification:

<img width="997" height="665" alt="Image" src="https://github.com/user-attachments/assets/870da759-7497-4cb2-a472-ae9cd54567c8" />

---

### 3. Install **GTKWave**

```bash

sudo apt-get update                                   # Install GTKWave
sudo apt install gtkwave

gtkwave                                               # Verify 
```

### Verification:

<img width="1205" height="137" alt="Image" src="https://github.com/user-attachments/assets/2313233d-9eff-4a01-abd1-0c2063b7761a" />


<img width="995" height="650" alt="Image" src="https://github.com/user-attachments/assets/6a475dce-5530-4baf-9852-381e0afe2d5a" />

