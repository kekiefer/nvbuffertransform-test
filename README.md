# NvBufferTransform Test

Checks whether NvBufferTransform preserves an alpha value in an ARGB->ARGB conversion

## Getting Code

git clone https://github.com/kekiefer/nvbuffertransform-test.git

## Building

### On target

    make

### Cross-compile

    TARGET_ROOTFS=/path/to/sdk/target/sysroot make

## Running

    ./nvbuffertransform_test
