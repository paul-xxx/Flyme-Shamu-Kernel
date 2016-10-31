# Flyme-Shamu-Kernel [![Build Status](https://travis-ci.org/ryanguy426/Flyme-Shamu-Kernel.svg?branch=android-msm-shamu-3.10-lollipop-release)](https://travis-ci.org/ryanguy426/Flyme-Shamu-Kernel)
### [LICENSE](https://raw.githubusercontent.com/ryanguy426/Flyme-Shamu-Kernel/android-msm-shamu-3.10-lollipop-release/LICENSE)

This Kernel is for Nexus 6 (shamu); Specifically for [Flyme 5.1.10.24R beta](http://flyme.cn/firmwarelist-33.html#6).

## Why?

* Good question. Two reasons: First, I personally enjoy Flyme, if only because MIUI hasn't made it to our device still (I've tried porting it, and get stuck in a bootloop).
* and second, the kernels I've tried to use with Flyme 5 have caused a bootloop of optimizing apps. This kernel doesn't have that issue, and allows the ROM to boot up without issues.
* <sup>*"IF YOU LIKE SUCH A SHITTY OS WHY DID YOU GET A NEXUS YOU FUCKBAG!!!?!?12T1HOPTGE"*</sup> Because I enjoy trying new things. and I enjoy Flyme.

## Features

* F2FS (***WIP - BROKEN***)
* CPU overclock to 2649MHz
* GPU overclock to 700MHz
* GPU underclock to 110MHz
* Zen Decision
* KCAL support
* MultiROM support (Kexec-hardboot)
* 1536kB readahead default
* [RAM overclock(?)](https://github.com/ryanguy426/Flyme-Shamu-Kernel/commit/5ee8d1353a5d267e60a3c99e78a43e76d6fc289d)
* Ofast and other optimizations
* More to come!

## Compatibility with other ROMS

This kernel is built off of [AOSP kernel source code for shamu](https://android.googlesource.com/kernel/msm.git/+/android-msm-shamu-3.10-lollipop-release) and as such could ***in theory*** be compatible with any AOSP 5.1.1 based ROM.

***If you use this kernel with any ROM besides Flyme 5.1.10.24R beta, you will not recieve any support! I also am not responsible for any damages incurred or issues resulting in you using this kernel on an unsupported ROM!***

## Contributing

Feel free to do so. Here's how you can!

1. Fork the repo
2. Create a new branch for the feature you're working on (ex. ReallyCoolGovenor)
3. Make your changes
4. Build the kernel ***and test it on your device for longer than five minutes! Stress test it!***
5. Push your changes to that branch **(NOT master/android-msm-shamu-3.10-lollipop-release!)**
6. If your changes are stable and don't cause any problems, create a pull request with this repo, along with a ***detailed*** description of what your changes are, and what they effect.

 ***If your pull request isn't detailed and easy to understand, it will not be merged.***
