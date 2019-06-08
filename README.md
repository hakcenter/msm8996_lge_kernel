MSM8996 LGE Kernel
=============

### Some links
* [LG V20] XDA thread.

### V20
- `H910` - AT&T (US)

* `H918` - T-Mobile (US)

* `US996` - US Cellular & Unlocked (US)

* `US996Santa` - US Cellular & Unlocked (US)
  * Unlocked with Engineering Bootloader

* `VS995` - Verizon (US)

* `H990DS` - International (Global)

* `H990TR` - Turkey (TR)

* `LS997` - Sprint (US)

* `H915` - Canada (CA)

* `F800K/L/S` - Korea (KR)

## COMPILE THE KERNEL

### Clone
	git clone https://github.com/hakcenter/msm8996_lge_kernel.git -b mko-v2

### Build
	./build.sh DEVICE && ./copy_finished.sh

* "DEVICE" will be one of the above names (case sensitive).
* You should also configure your compiler path in ´build.sh´.

## A bit of info

This is the Oreo branch.
It builds workable kernels for all above devices.

Branch 'lge-3.18-stable', like the name implies, is an upstreamed base LG kernel with
various fixes - for convenience sake. It can be an ideal starting point for other's
wanting to try kernel development for LG's MSM8996 devices.

[LG V20]: <https://forum.xda-developers.com/v20/development/>
