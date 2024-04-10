# cg3-stm32l476
Light and extremely minimal starting point for STM32L476

No ST libraries like HAL or LL, but include register definitions, startup, linker, etc. 

Dependancy only on [gcc-arm-none-eabi](https://packages.debian.org/bookworm/gcc-arm-none-eabi) and [pyocd](https://packages.debian.org/stable/embedded/python3-pyocd) 

Mainly used with [Orbital Platform](https://github.com/uwu64/orbital-platform)

Try `make clean`, `make`, and `make flash`
