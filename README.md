# personal-mpv-configuration
My personal-mpv-configuration file for the mpv media player in conjuction with the scripts and shader upscalers I use for watching anime.

Tuned for my personal desktop: Ryzen 5800X3D -30 CO All Core /\ Radeon RX6950XT GFXClk OC @~2833mhz | MEMClk OC @~2400Mhz Fast Timings | Fclk OC @~2150Mhz /\ Corsair Vengeance 32GB OC @1.4V @3600Mhz CL16 tRCD19 tRP19 tRAS37

Colorspace management settings optimized for my display and adjusted for my personal preferences: Corsair Xeneon 32QHD165 100% AdobeRGB | 100% SRGB | 98% DCI-P3 | 86% BT.2020 /\ Using AMD Freesync, AMD Virtual Super Resolution, and GPU-scaling /\ Display is running at 4k 3840x2160@165Hz 8bit+FRC ACM Dithering for 10bit DCI-P3 and AMD Vivid Gaming to counter the washed out colors /\

This configuration is being used with the latest git mpv build from (https://github.com/zhongfly/mpv-winbuild) and SmoothVideoPlayer4 @ X5 Source ~119.880fps.

Here is a screenshot of my SPV4 settings that I am using currently for smooth realtime motion vector interpolation:
<img width="453" alt="373946153-50ad95de-38a4-464a-96f5-ea69dcdc8ad7" src="https://github.com/user-attachments/assets/5be87b2d-5211-48c2-8ce7-5daf974517ed">

Here is another screenshot of the settings that I am currently using in AMD Software: Adrenaline Edition for mpv.exe:
<img width="1296" alt="373250147-fceff9e0-2ff2-4b60-af30-d8f9f3492dc4" src="https://github.com/user-attachments/assets/7327393a-242b-4572-97ae-40089b3b1af4">

Here is one final screenshot of graphics settings of mpv.exe in the Windows 11 settings app, with its registry values:
<img width="749" alt="372825095-0b2f88da-540f-4bf7-b4ef-be13f8a6a700" src="https://github.com/user-attachments/assets/597ffc58-cae8-4c0e-bdd0-7f0ebc191ed4">

Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences | Value Name: C:\Users\Admin\Documents\mpv\mpv.exe Value Data: AutoHDREnable=48;VRROptimizeEnable=0;SwapEffectUpgradeEnable=1;SwapEffectUpgradeCache=1;GpuPreference=2;DisableMultiplaneOverlay=1;AutoColorManagementSupported=1;AutoColorManagementEnabled=1;
