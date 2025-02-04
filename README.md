# personal-mpv-configuration
My personal-mpv-configuration file for the mpv media player in conjuction with the scripts and shader upscalers I use for watching anime.

Tuned for my personal desktop: Ryzen 7 5800X3D -30 All Core CO /\ XFX Mecury Radeon 7900XTX /\ Corsair Vengeance LPX 32GB DDR4

Colorspace management settings optimized for my display and adjusted for my personal preferences: Xiaomi G Pro 27 100% SRGB, 100% AdobeRGB, 99% DCI-P3, 86% BT.2020

Display signal mode is running at 4K 3840x2160@180Hz 10bit Native Colorspace for SDR WCG while using Desktop Mode: 4K 3840x2160@120Hz during playback

This configuration is being used with the latest git mpv build from (https://github.com/zhongfly/mpv-winbuild) and SmoothVideoPlayer4 @ X5 Source ~119.880fps.

Here is a screenshot of my SPV4 settings that I am using currently for smooth realtime motion vector interpolation:
<img width="452" alt="{6D879425-254D-4E44-BE94-A80268E2256A}" src="https://github.com/user-attachments/assets/072a206d-c6a2-4b54-ae8b-6e6f641705b4">

Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences | Value Name: C:\Users\Admin\Documents\mpv\mpv.exe Value Data: VRROptimizeEnable=0;SwapEffectUpgradeEnable=1;SwapEffectUpgradeCache=1;GpuPreference=2
