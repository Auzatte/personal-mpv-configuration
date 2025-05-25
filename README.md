This repository can sometimes be purged by myself sometimes just to freeup commit history that sometimes clutters it, but it will be remade with the same name right after when this does occur so it should not break any link to it that could've possibly have been made to it as long as it is not during the time before recreation.
All the files provided in here are just so I can show what I am currently using. I did not make any of the fonts, scripts, etc. myself other than the mpv.conf file itself which was informed from gathering information from the world wide web and the mpv wiki page.
Credit for those files that were not created by me goes completely towards their respective owners and creators.

# Tuned for my personal desktop (Desktop Battlestation Specifications)

Processor: AMD Ryzen 7 5800X3D 4.5GHz Boost with -30 Curve Optimizer applied All Core

Graphics Card: AMD Radeon XFX Mercury Magnetic Air 7900XTX (AQUA Liquid BIOS Flashed) | GFXClk Min @2935MHz GFXClk Max @3300MHz | MEMClk Fast Timings @2664MHz (@2650MHz due to -14MHz offset)

Motherboard: ASUS ROG STRIX B550-F (Heavily Tweaked BIOS Settings)

RAM: G.SKILL Ripjaws 32GB (2x16GB) 4000MHz CL18 | Infinity Fabric: 2000MHz

Storage: Fantom Drives VENOM8 2TB Gen 4 M.2 NVMe | Read: 7400MB/s Write: 6900MB/s

# Monitor Specifications

Monitor: Xiaomi G Pro 27i 180Hz | 100% SRGB, 97% AdobeRGB, 99% DCI-P3, 81.9% BT.2020 | SDR Peak ~1037nits, HDR Peak ~1500nits| 1152 Local Dimming Zones

Display Mode: 4K 3840x2160@120Hz 10bit HDR | VRR+VSR Enabled

Signal Mode: 1440p 2560x1440@180Hz 10bit HDR

# General Information

This configuration is being used with the latest git mpv build provided by Zhongfly's repoistory (https://github.com/zhongfly/mpv-winbuild) & the latest stable release of SmoothVideoProject (https://www.svp-team.com/).

# General Settings
**AMD Radeon Software Settings**

<img width="1450" alt="{2E77A093-6761-459D-A30B-762F64E3502A}" src="https://github.com/user-attachments/assets/a330f06a-8b9b-4487-b25b-cb9ea480b3bd" />

**SmoothVideoPlayer4 Settings**

<img width="528" alt="{8061D6F2-07F6-4536-B8BD-AAE8DCD87831}" src="https://github.com/user-attachments/assets/2a11ca3d-1097-434f-8765-2760176c6207" />

**Windows Graphics Settings**

<img width="634" alt="{1CDE196F-0AD8-4FE8-B703-C1B7193C17CE}" src="https://github.com/user-attachments/assets/a884cd60-30a7-4c46-996b-1e6fb2c70bd7" />

Registry Path: Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences

Value Name: C:\Users\Admin\Documents\mpv\mpv.exe | Value Data: VRROptimizeEnable=1;AutoHDREnable=48;SwapEffectUpgradeEnable=257;SwapEffectUpgradeCache=1;GpuPreference=2

# Note
I absolutely refuse to use RIFE AI Interpolation as it is way more damaging to the original content when compared to SVP4's own interpolation methods.
RIFE AI can and will either completely destroy the real original frames or make original frames completely vanish when used.

At least with SVP4's interpolation it will keep all the original frames untouched by add its own calculated interpolated frames onto it.
The most visible artifacting to be seen with my current setup usually appears on lower quality encodes rather than higher quality encodes.
Usually in the form of either a "Halo Soap Opera Motion Effect" around characters in slower motion against a very detailed background or "Wavy Distorted Lines" around characters feet during motion on stairs.

Finally, I am always open to people's suggestions to further enhance the quality and performance of my mpv configuration file especially if they understand and know more about the subject than I currently do.
Also, I welcome any mpv media player script recommendations as well if you think it'll enhance my general use of the player itself.
