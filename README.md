> A [paid version of Ukuu](https://teejeetech.in/tag/ukuu/) is now available with more features and a new UI. This repository contains source code for v18.9 and previous versions.

### Ubuntu Kernel Update Utility (Ukuu)

This is a tool for installing the latest mainline Linux kernel on Ubuntu-based distributions.

![](https://2.bp.blogspot.com/-76C_l3BcJyg/WNdzTpSoiKI/AAAAAAAAGKs/xOvB-LCH2cYiDpdbqWkeOLhY9I7TVACJwCLcB/s1600/ukuu_main_window.png)

### Features

*   Fetches list of kernels from [kernel.ubuntu.com](http://kernel.ubuntu.com/~kernel-ppa/mainline/)
*   Displays notifications when a new kernel update is available.
*   Downloads and installs packages automatically

### Downloads & Source Code 
Original Ukuu is written using Vala and GTK3 toolkit by TeejeeTech (Tony George http://teejeetech.in) Original Source code and binaries are available from https://github.com/teejee2008/ukuu.

This modified version availible from the [GitHub project page](https://github.com/paullittrell/ukuu).

### Build instruction

#### Ubuntu-based Distributions (Ubuntu, Linux Mint, Elementary, etc)  

 in a terminal window:  

    sudo apt-get install libgee-0.8-dev libjson-glib-dev libvte-2.91-dev valac
    git clone https://github.com/paullittrell/ukuu.git
    cd ukuu
    make all
    sudo make install
