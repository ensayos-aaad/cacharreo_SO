# cacharreo_SO

Este es un primer ensayo

## Instalacion qemu


De la pagina: https://pdos.csail.mit.edu/6.828/2023/tools.html


```
sudo apt-get install git build-essential gdb-multiarch qemu-system-misc gcc-riscv64-linux-gnu binutils-riscv64-linux-gnu 
```

Siguiendo la sección **Testing your Installation**:


```
(base) tigarto@tigarto-PC:~$ qemu-system-riscv64 --version
QEMU emulator version 6.2.0 (Debian 1:6.2+dfsg-2ubuntu6.21)
Copyright (c) 2003-2021 Fabrice Bellard and the QEMU Project developers
(base) tigarto@tigarto-PC:~$ riscv64-linux-gnu-gcc --version
riscv64-linux-gnu-gcc (Ubuntu 11.4.0-1ubuntu1~22.04) 11.4.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

(base) tigarto@tigarto-PC:~$ riscv64-unknown-elf-gcc --version
Command 'riscv64-unknown-elf-gcc' not found, but can be installed with:
sudo apt install gcc-riscv64-unknown-elf
(base) tigarto@tigarto-PC:~$ riscv64-unknown-linux-gnu-gcc --version
riscv64-unknown-linux-gnu-gcc: command not found
(base) tigarto@tigarto-PC:~$ ^C
(base) tigarto@tigarto-PC:~$ 
```

Toco instalar:

```
sudo apt install gcc-riscv64-unknown-elf
```


El ultimo no dio.

Vamos a git clone:

```
git clone https://github.com/mit-pdos/xv6-public.git
cd xv6-public
make qemu
```












### Referencias

* https://1984.lsi.us.es/wiki-ssoo/index.php/Xv6
* https://www.assistedcoding.eu/2017/11/06/install-vx6-operating-system/
* https://oslab.kaist.ac.kr/xv6-install/?ckattempt=1
* https://pdos.csail.mit.edu/6.828/2023/

