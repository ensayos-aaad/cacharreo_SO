# Ejecución del xv6


## Prerequisitos



```
apt-get install qemu-system
```


https://pdos.csail.mit.edu/6.1810/2023/tools.html


https://pdos.csail.mit.edu/6.828/2023/labs/util.html


Herramientas para compilar y crosscompilar

```
sudo apt-get install git build-essential gdb-multiarch gcc-riscv64-linux-gnu binutils-riscv64-linux-gnu 
```

Testeando la instalación:

```
qemu-system-riscv64 --version
riscv64-linux-gnu-gcc --version
```

Luego vamos a instalar https://pdos.csail.mit.edu/6.828/2023/xv6.html



```
git clone https://github.com/mit-pdos/xv6-riscv.git
git clone https://github.com/mit-pdos/xv6-riscv-book.git
```

Ahora:

```
cd xv6-riscv
make qemu
```

No dio


To quit qemu type: Ctrl-a x (press Ctrl and a at the same time, followed by x).




https://github.com/remzi-arpacidusseau/ostep-projects/blob/master/INSTALL-xv6.md






