# RPI4-Custom-Image
Embedded Linux Build Root for Raspberry Pi 4 Step-By-Step.

Overview
In this tutorial we will build and configure a minimal image for raspberry pi 4 with customized toolchain, uboot, kernel and root filesystem.

Required hardware
Linux Machine OS (ex: Ubuntu 20.04 LTS)
Raspberry Pi 4
SD Card >= 2gb
SD Card Reader
USB to TTL (PL2303)
Major Steps
Configure the SD Card
Configure and build the Toolchain
Building the Bootloader
Config and Build the Kernel
Create the root filesystem
Boot the RPI4
SD Card Configuration
Plug in the SD Card
Open Disks app (Ubuntu)
Format the SD Card
Creat two partitions
(a) boot : [100 - 500] MB = FAT format
(b) root : Remaining size = Ext4 format
Mount the Partitions from the "Play" Symbol
