# repo.blacksky3.com

This is the home page for repo.blacksky3.com.

# Available repository

- blacksky3

- kernel

- llvm 

- toolchain

# blacksky3 repo

This repository contain various package that are used for gaming purpose with it's dependencies packages. All build from source, that means it's a -git package.

## Package build order

- spirv-headers -> spirv-tools

- glslang

- vulkan-headers -> vulkan-icd-loader -> lib32-vulkan-icd-loader -> vulkan-validation-layers -> lib32-vulkan-validation-layers -> vulkan-extensionlayers -> lib32-vulkan-extensionlayers -> vulkan-tools
