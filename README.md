# personal-mpv-configuration
My personal-mpv-configuration file for the mpv media player in conjuction with the scripts and shader upscalers I use for watching anime.

Tuned for my personal desktop: Ryzen 5800X3D -30 CO All Core /\ Radeon RX6950XT GFXClk OC @~2819mhz | MEMClk OC @~2412Mhz Fast Timings | /\ Corsair Vengeance 32GB OC @1.4V @3600Mhz CL16 tRCD19 tRP19 tRAS37

Colorspace management settings optimized for my display and adjusted for my personal preferences: Corsair Xeneon 32QHD165 Calibrated Results: Max Luminance 427cd/m², Color Gamut Coverage Relative to Reference Colorspace | 142.5% SRGB | 122.1% AdobeRGB | 113.6% DCI-P3 | 82.7% BT.2020

Using AMD Virtual Super Resolution and GPU-scaling /\ Display is running at 4k 3840x2160@165Hz 8bit+FRC ACM Dithering for 10bit

This configuration is being used with the latest git mpv build from (https://github.com/zhongfly/mpv-winbuild) and SmoothVideoPlayer4 @ X5 Source ~119.880fps.

Here is a screenshot of my SPV4 settings that I am using currently for smooth realtime motion vector interpolation:
<img width="452" alt="{2E2D5C1E-D46C-423A-9C54-F8E8F925B196}" src="https://github.com/user-attachments/assets/db4ef7d9-a56a-4098-b6e8-86375858eb94">

Here is another screenshot of the settings that I am currently using in AMD Software: Adrenaline Edition for mpv.exe:
<img width="1296" alt="373250147-fceff9e0-2ff2-4b60-af30-d8f9f3492dc4" src="https://github.com/user-attachments/assets/7327393a-242b-4572-97ae-40089b3b1af4">

Here is one final screenshot of graphics settings of mpv.exe in the Windows 11 settings app, with its registry values:
![{720FA2BD-F306-4536-ACEA-BAA71DCCFD5A}](https://github.com/user-attachments/assets/65964d42-0aae-4c2e-b5e2-04c74768c5e2)

Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences | Value Name: C:\Users\Admin\Documents\mpv\mpv.exe Value Data: VRROptimizeEnable=0;AutoHDREnable=48;SwapEffectUpgradeEnable=0;SwapEffectUpgradeCache=0;GpuPreference=2;AutoColorManagementSupported=1;AutoColorManagementEnabled=1;

mpv.exe set to Disable Fullscreen Optimizations, Run as Administrator, & Override High DPI scaling behavior. Scaling performed by: Application
