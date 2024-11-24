# Lenovo S145-15IWL OC EFI for MacOS Sequoia

## Introduction

This is Lenovo S145-15IWL hackintosh configuration for OpenCore 1.0.2 and it is 90% working.

 - This configuration has been tested on Sequoia 15.1.

## Hardware configuration

 - Intel i3-8145u
 - Intel HD graphic 620
 - Screen 1920 x 1080 (FHD) TN
 - 128GB NVMe SSD
 - 1Tb hard disk
 - 8 GB DDR4 RAM
 - Nvidia MX110 GPU card (disabled in BIOS)
 
 ## What is working
 - Audio on speakers and Audio jack connector
 - Brightness control
 - ELAN touchpad
 - SD card reader
 - Graphic acceleration with Intel UMA because NVIDIA is disabled

 ## What is not working
 - Nvidia GPU
 - Realtek wifi chip

## Bios

In `BIOS` disable:

 - Intel Vt-d
 - WIFI chip
 - set display device to UMA

