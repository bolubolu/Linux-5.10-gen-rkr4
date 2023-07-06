# Rockchip Linux SDK
rk3588_linux_release_v1.1.0_20230420.xml


Rockchip Linux SDK for the Rockchip SOC boards
  - wiki <http://opensource.rock-chips.com/wiki_Main_Page>.

## Quick Start

1. Check supported targets:
```shell
   ~ $ make help
```
2. Choose SDK's defconfig:
```shell
   ~ $ make rockchip_defconfig
```
3. Change SDK's configs:
```shell
   ~ $ make menuconfig
   ~ $ make savedefconfig
```
4. Run "make" to build the images, logs saved at "output/log/"
5. Flash the generated "output/firmware/update.img" to your device
6. Boot your device and enjoy it
