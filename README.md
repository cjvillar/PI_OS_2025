# RSPRY OS 25
Learning how to make a simple OS for the Raspberry **Pi Zero**.

### 1. [First we learn cross-compiling: compile an os from an existing os](https://wiki.osdev.org/Raspberry_Pi_Bare_Bones)





### Tools (Mac):
QEMU:

```bash
brew install qemu
qemu-system-arm --version
```

ARM-GNU Compiler:
```bash
brew install arm-none-eabi-gcc
```
or 

[arm Developer](https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads)



run:
```bash
make clean
make
```

qemu-system-arm -m 512 -M raspi0 -serial stdio -kernel myos.elf
qemu-system-arm -m 1G -M raspi2b -serial stdio -kernel myos.elf

### resources:
https://wiki.osdev.org/Raspberry_Pi_Bare_Bones
https://www.qemu.org/docs/master/system/arm/raspi.html
https://jsandler18.github.io/tutorial/dev-env.html
https://wiki.osdev.org/Raspberry_Pi_Bare_Bones



