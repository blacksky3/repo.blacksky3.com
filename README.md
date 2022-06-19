# repo.blacksky3.com

This is the home page for repo.blacksky3.com.

# Available repository

- blacksky3

- kernel

- llvm 

- toolchain

# blacksky3 repo

This repository contains various package that are used for gaming purpose with it's dependencies packages. All build from source, that means it's a -git package.

### Package build order

- spirv-headers -> spirv-tools

- glslang

- vulkan-headers -> vulkan-icd-loader -> lib32-vulkan-icd-loader -> vulkan-validation-layers -> lib32-vulkan-validation-layers -> vulkan-extensionlayers -> lib32-vulkan-extensionlayers -> vulkan-tools

- opencl-headers -> opencl-clhpp -> ocl-icd -> lib32-ocl-icd

- libdrm -> lib32-libdrm

- libglvnd -> lib32-libglvnd

- directx-headers

- mesa-git -> lib32-mesa-git

- amdvlk -> lib32-amdvlk

- vkd3d -> lib32-vkd3d

- vkd3d-proton -> lib32-vkd3d-proton -> vkd3d-proton-bin

- vkbasalt -> lib32-vkbasalt

# kernel repo

This repository contains various kernel build with custom kernel patches.

### Available packages

##### From XanMod

- linux-xanmod-edge

- linux-xanmod

- linux-xanmod-lts

- linux-xanmod-tt

##### From Zen/Liquorix source

- linux-lqx

- linux-lqx-pds

- linux-lqx-bmq

##### From Manjaro

- linux515

- linux518

##### From Archlinux

- linux-bore

- linux-tt

- linux-cacule

- linux-cacule-rdb

- linux-pds

- linux-bmq

- linux-rt

- linux-rc

- linux-git

- linux-lts-bore

- linux-lts-pds

- linux-lts-bmq

- linux-lts-cacule

- linux-lts-cacule-rdb

- linux-lts-tt

- linux-lts-tt-cfs

## llvm repo

This repository contains all of the LLVM toolchain build from source. That means it's a -git package. It is build against the blacksky3 repo. Why so? Because spirv-llvm-translator depends on spirv-headers (git version).
