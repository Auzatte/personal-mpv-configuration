This repository can sometimes be purged by myself sometimes just to freeup commit history that sometimes clutters it, but it will be remade with the same name right after when this does occur so it should not break any link to it that could've possibly have been made to it as long as it is not during the time before recreation.

All the files provided in here are just so I can show what I am currently using. I did not make any of the fonts, scripts, etc. myself other than the mpv.conf file itself which was informed from gathering information from the world wide web and the mpv wiki page.

Credit for those files that were not created by me goes completely towards their respective owners and creators.

# Tuned for my personal desktop (Desktop Battlestation Specifications)

Processor: AMD Ryzen 7 5800X3D 4.5GHz Boost with -30 Curve Optimizer applied All Core

Graphics Card: AMD Radeon XFX Mercury Magnetic Air 7900XTX | GFXClk @3200MHz | UV @1125mV | MEMClk Fast Timings @2664MHz

Motherboard: ASUS ROG STRIX B550-F (Heavily Tweaked BIOS Settings)

RAM: G.SKILL Ripjaws 32GB (2x16GB) 4000MHz CL18 | Infinity Fabric: 2000MHz

Storage: Fantom Drives VENOM8 2TB Gen 4 M.2 NVMe | Read: 7400MB/s Write: 6900MB/s

# Monitor Specifications

Monitor: LG UltraGear Tandem OLED 280Hz | 100% SRGB, 99.5% AdobeRGB, 99.5% DCI-P3, 82% BT.2020 | VESA DisplayHDR True Black 500

Minimum Luminance: 0.0005cd/m² | Maximum Luminance: 1497cd/m² | Maxmimum Full-Frame Luminance: 603cd/m²

Signal Mode: 2560x1440 @ 280Hz 12-bit depth | Desktop Mode: 3840x2160 @ 120Hz 12-bit depth

# General Information

This configuration is being used with the latest git mpv build provided by Zhongfly's repoistory (https://github.com/zhongfly/mpv-winbuild) & the latest stable release of SmoothVideoProject (https://www.svp-team.com/).

# General Settings
**AMD Radeon Software Settings**

<img width="1453" height="1017" alt="{97609C2C-17FD-452B-B56D-42C3C54A0407}" src="https://github.com/user-attachments/assets/52e17c30-2549-4c6c-8ddf-49594771820d" />

**SmoothVideoPlayer4 Settings**
Best Settings Utilizing SVP4 Interpolation Engine for 4K120fps playback

<img width="522" height="512" alt="{3BE49585-B68D-4E21-B510-74D18E2EAAA1}" src="https://github.com/user-attachments/assets/b24ccf40-af9b-4d68-8e56-f405960037f1" />

Forcing an exact multiplier leads to less CPU usage as well as less power since it is easier to compute than forcing a fixed framerate.

**Windows Graphics Settings**

<img width="595" height="208" alt="{89253669-2A02-4CAA-AA2F-D24D3E03BD3A}" src="https://github.com/user-attachments/assets/1f449bcc-613a-4f04-8a62-2d226d95778a" />

Registry Path: Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences

Value Name: C:\Users\Admin\Documents\mpv\mpv.exe | Value Data: VRROptimizeEnable=0;AutoHDREnable=48;SwapEffectUpgradeEnable=1;SwapEffectUpgradeCache=1;GpuPreference=2

# Note
I absolutely refuse to use RIFE AI Interpolation as it is way more damaging to the original content when compared to SVP4's own interpolation methods.
RIFE AI can and will either completely destroy the real original frames or make original frames completely vanish when used.

At least with SVP4's interpolation it will keep all the original frames untouched by add its own calculated interpolated frames onto it.
The most visible artifacting to be seen with my current setup usually appears on lower quality encodes rather than higher quality encodes.
Usually in the form of either a "Halo Soap Opera Motion Effect" around characters in slower motion against a very detailed background or "Wavy Distorted Lines" around characters feet during motion on stairs.
