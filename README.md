My personal-mpv-configuration file for the mpv media player in conjuction with the scripts and shader upscalers I use for watching anime.

Tuned for my personal desktop: Ryzen 5800X3D -30 CO All Core | Radeon RX6950XT OC @ 2700Mhz-2800Mhz Core / @ 2412Mhz Memory Fast Timings \ UV @ 1162mV | Corsair Vengeance 32GB OC @ 3600MhzCL19 1.4V

Colorspace management settings optimized for my display and adjusted for my personal preferences: Corsair Xeneon 32QHD165

This configuration is being used with the latest mpv-git release and with SmoothVideoPlayer4 interpolation @5x23.976fps 119.880fps.

Below is a screenshot of my personal SVP4 settings I use for maximum fluidity with minimal contouring:
<img width="449" alt="SVP4-Settings" src="https://github.com/Auzatte/personal-mpv-configuration/assets/169538073/d2893d68-9edc-4a5a-bac5-79a9f79a391b">

Suprisingly enough this configuration can be configured to work on very low-end devices such as my laoptop that is powered by an i3-6100U with only a little quality reduction granted that is without the usage of SVP4 and glsl shaders as well as you adjust the mpv-configuration file accordingly toward your devices capabilites specifically within the caching settings and threading settings without overduing it. Also, by choosing sws as the video filter scaler instead of zimg scaler and just specify the sws scaler settings that are similar to zimg for little quality degradation for example zimg-bitexact=yes becomes sws-scaler=spline & zimg-fast=no becomes sws-fast=no. Unfortunately, if we specify a scaler different from sws's default it becomes a frame dropping mess though. Overall it removes/changes aproximately 30lines from the original configuration to make this work and most of those lines mainly consisted of removing windows only settings so this could work on linux and android only about 12 lines that were removed/changed have an effect on video and audio quality.
