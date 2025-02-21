# personal-mpv-configuration
My personal-mpv-configuration file for the mpv media player in conjuction with the scripts and shader upscalers I use for watching anime.

Tuned for my personal desktop: Ryzen 7 5800X3D -30 All Core CO /\ XFX Mecury Radeon 7900XTX

Colorspace management settings optimized for my display and adjusted for my personal preferences: Xiaomi G Pro 27 |100% SRGB, 100% AdobeRGB, 99% DCI-P3, 86% BT.2020| /\SDR Peak ~1037nits, HDR Peak ~1500nits/\ 1152 Local Dimming Zones

Display is running at Signal Mode: 4K 3840x2160@180Hz 10bit | Desktop Mode: 4K 3840x2160@120hz 10bit

This configuration is being used with the latest git mpv build from (https://github.com/zhongfly/mpv-winbuild) and SmoothVideoPlayer4 @ X5 Source ~119.880fps.

Here is a screenshot of my SPV4 settings that I am using currently for smooth realtime motion vector interpolation:
<img width="453" alt="{C8837F82-85E0-4E6F-9330-91D8896DA3D0}" src="https://github.com/user-attachments/assets/fbde69b5-e810-4515-a5ea-170170e388ac" />

Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences
Value Name: C:\Users\Admin\Documents\mpv\mpv.exe Value Data: VRROptimizeEnable=0;SwapEffectUpgradeEnable=1;SwapEffectUpgradeCache=1;GpuPreference=2
Compatibility Tab on mpv.exe set to Disable Fullscreen Optimizations & High DPI Scaling Override set to Application
