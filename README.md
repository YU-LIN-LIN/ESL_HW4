# ESL_HW4

Cross-compile Gaussian Blur to RISC-V VP platform.
Here just provide the main part of Gaussian Blur to RISC-V VP platform.
Need to git clone source code from https://github.com/agra-uni-bremen/riscv-vp.git to construct riscv platform.

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

