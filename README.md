# TWRP device tree for UMIDIGI F2

## About Device

![UMIDIGI F2](https://www.umidigi.com/new/Images/f2/blue-f2.png)

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | Octa-core (4xCortex-A73, 2.1GHz & 4xCortex-A53, 2.0GHz)) Helio P70
AI Cores | 2 cores APU
Platform | MediaTek MT6771(T)
GPU     | Mali G72 MP3 900MHz
architecture | 64 bit
Memory  | 6GB LPDDR4X RAM
Shipped Android Version | 	Android 10
Storage | 128 GB UFS 2.1 (expandable storage up to 256GB (VFAT))
Battery | 5150 mAh
Height | 162.6 mm
Width | 77.7 mm
Thickness | 8.7 mm
Weight | 215g
Display | 6.53" (16.5862 cm) FullView Display
Aspect Ratio | 19.5:9
Screen resolution | 2340 x 1080 pixels
Video | 1080p, 720p video, 30fps, FHD+
Primary Camera | 48MP + 5MP (depth), Samsung GM1,1/2'' image sensor, F/1.79 aperture, 6-element lens, 0.8μm pixel(support 4-in-1 super pixel, 0.8μm synthesis 1.6μm)
Wide Angle Camera | 13MP, FOV 120°
Macro Camera | 5MP, 2cm distance
Secondary Camera | 32MP, 5-element lens, F/2.0 aperture, Selfie countdown, Face recognition
Quick charging | Yes, 18W
Wifi | Yes, IEEE802.11 a/b/g/n, Supports 5G Wi-Fi Signal / Wi-Fi Direct / Wi-Fi Display
Bluetooth | v4.2, Bluetooth HID
USB type C | Yes
NFC | Yes, supports read/write, card emulation, and P2P
Network support | Both SIM slots are compatible with 4G, support 4G VoLTE in both slots simultaneously
GPRS | Available
EDGE | Available
SIM size | SIM1: Nano, SIM2: Nano (Hybrid)
Sensors | P/L-Sensors, Accelerometer, Gyroscope, Geomagnetic Sensor

Network | Bands
-------:|:-------------------------
2G | GSM: B2 /B3 /B5 /B8
2G | CDMA1X: BC0 /BC1
3G | CDMA EVDO: BC0 /BC1
3G | WCDMA: B1 /2 /4 /5 /6 /8
3G | TD-SCDMA: B34 /39
4G | TTDD-LTE: 34 /38 /39 /40 /41
4G | FDD-LTE: B1 /2 /3 /4 /5 /6 /7 /8 /12 /13 /17 /18 /19 /20 /26 /28A /28B /66 /71

**This device tree can be used to build twrp for UMIDIGI F2**


## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_f1_play-eng
mka recoveryimage
```
