# mbed-epaper
mbed library for Good Display E-paper (like GDEW042Z15)
referenced on the https://github.com/soonuse/gdew042z15_4.2inch_e-paper_b libraries

## compile mbed:

1. download mbed library (only once)
``` powershell
mbed deploy
```

2. to compile
``` powershell
mbed compile -f
```

3. When using the NUCLEO-L073RZ, use the following command
```
mbed compile -f -m NUCLEO_L073RZ -t GCC_ARM
```