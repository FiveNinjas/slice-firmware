# slice-firmware
BCM270x firmware related stuff for Slice

## Firmware d-blob.bin

Slice needs the correct dt-blob.bin on the root of the FAT (boot) partition to set up the initial pin states and clocks correctly.

Use the compile.sh script to generate the required dt-blob.bin from slice-dt-blob.dts
