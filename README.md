# personal-mpv-configuration
My personal-mpv-configuration file for the mpv media player in conjuction with the scripts and shader upscalers I use for watching anime.

Tuned for my personal desktop: Ryzen 7 5800X3D -30 All Core Curve Optimizer /\ ASRock Formula OC Radeon RX6950XT /\ Corsair Vengeance LPX 32GB 3600MHz CL16

Colorspace management settings optimized for my display and adjusted for my personal preferences: Corsair Xeneon 32QHD165 Calibrated Results: Max Luminance 426cd/m², Color Gamut Coverage Relative to Reference Colorspace | 142.5% SRGB | 122.1% AdobeRGB | 113.6% DCI-P3 | 82.7% BT.2020

Using AMD Virtual Super Resolution and GPU-scaling /\ Display is running at 4k 3840x2160@165Hz HDR 8bit+FRC ACM Dithering for 10bit

This configuration is being used with the latest git mpv build from (https://github.com/zhongfly/mpv-winbuild) and SmoothVideoPlayer4 @ X5 Source ~119.880fps.

Here is a screenshot of my SPV4 settings that I am using currently for smooth realtime motion vector interpolation:
<img width="452" alt="{6D879425-254D-4E44-BE94-A80268E2256A}" src="https://github.com/user-attachments/assets/072a206d-c6a2-4b54-ae8b-6e6f641705b4">

Here is another screenshot of the settings that I am currently using in AMD Software: Adrenaline Edition for mpv.exe:
<img width="1445" alt="{3D810E57-C767-408F-89AE-D37881FF81D3}" src="https://github.com/user-attachments/assets/af839409-735d-4a36-9378-c0ade3bdf3ed" />

Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences | Value Name: C:\Users\Admin\Documents\mpv\mpv.exe Value Data: VRROptimizeEnable=0;AutoHDREnable=48;SwapEffectUpgradeEnable=1;SwapEffectUpgradeCache=1;GpuPreference=2;
