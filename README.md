# ESL_HW4

Cross-compile Gaussian Blur to RISC-V VP platform

## Compile 

### Build the "basic-acc-gaussian" platform of riscv-vp.
  cd riscv-vp/vp
  mkdir build
  cd build
  cmake ..
  make install

### Build Gaussian filter software
  cd riscv-vp/sw/basic-gaussian
  make
  make sim

