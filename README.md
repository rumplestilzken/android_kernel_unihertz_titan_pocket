# Build Instructions
To build the kernel, you must satisfy all build requirements.

This guide assumes you are working on a debian based system. My build system is based on Linux Mint 20.3.
I have done a lot of development with this machine, and may have software dependencies you don't, if you run into missing software, please make a ticket so that I update this documentation accordingly.

## Clone Git Repo
```
git clone git@github.com:rumplestilzken/unihertz_titan_kernel.git
```
## Install Build Dependencies 
```
sudo apt install build-essential libssl-dev gcc-aarch64-linux-gnu
```
## Build Kernel 
```
cd unihertz_titan_kernel
export CROSS_COMPILE="aarch64-linux-gnu-" # This is my version of the cross compiler, yours may be different
export CONFIG_MTK_GPIO=y # fixes pinctrl-mtk-common-v2_debug duplicate functions
```

Modify include/kernel/config/auto.conf key CONFIG_SYSTEM_TRUSTED_KEYS value to ""

```
make ARCH=arm64 titan_ufs_defconf
make ARCH=arm64
```

# Credits to NotKit for providing a base with which to start this development.

