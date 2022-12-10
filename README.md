# NEORV32-DE0-nano
RISC-V NEORV32 implementation for DE0-Nano, with SW examples (Fill in the build steps)

Among other things this repo documents the steps to build and run the NEORV32 implementation on a DE0-nano.

The development environment for this work is:
1. Ubuntu 22.04
2. Quartus versions 13.1, 15.1 and 18.1 running in an Ubuntu 16.04 Docker image
3. Quartus versions 20.1, 21.1 and 22.1std running native
4. RISC-V GCC [toolchain](https://www.emb4fun.de/riscv/neorv32/index.html)

The first step is to compile and load the VHDL into the FOGA in the DE0-nano, this process uses the Quartus tool. The examples in neorv32-examples were developed with 15.1. Quartus 20.1 seems to be the last version with the SDRAM IP and good DE0-nano support but I was unable to flash the bits to the DE0-nano so I've been using 15.1.

In addition to the github repo for neorv32-examples there is a [webpage](https://www.emb4fun.de/riscv/neorv32/index.html) that goes into more detail. Another [github repo](https://www.emb4fun.de/riscv/neorv32/index.html) of interest and the original [NEORV32 repo](https://www.emb4fun.de/riscv/neorv32/index.html)
